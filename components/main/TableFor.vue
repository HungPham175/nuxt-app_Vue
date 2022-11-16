<template>
  <div class="text-end grid grid-cols-4 lt-md:grid-cols-2 items-center border-b border-gray-100 p-7 lt-md:p-4"
    v-for="list in Lists">
    <div class="lt-md:items-start">
      <img :src="list.img" alt="mạng kém" class="max-w-full" />
    </div>
    <div>
      <p class="text-xl lt-md:text-sm font-semibold">{{ list.moneyReceived }} EUR</p>
      <p class="text-sm text-red-700">
        <img src="../../public/lower.svg" class="px-1 pb-1" />
        {{ list.received }}
      </p>
    </div>
    <div class="lt-md:hidden">
      {{ list.ConversionCost }} GBP
    </div>
    <div class="lt-md:hidden">
      {{ list.exchangeRate }}
      <img src="../../public/Crile.svg" class="items-center" />
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from "#imports";

let Lists = ref([
  {
    img: '../../dragon.png',
    moneyReceived: '1,185.00 EUR',
    received: '-7.64',
    ConversionCost: '1.99',
    exchangeRate: '1.19854',
  },
  {
    img: '../../techcom.png',
    moneyReceived: '1,178.68',
    received: '-7.64',
    ConversionCost: '25.00',
    exchangeRate: '1.19854',
    title: ""
  },
  {
    img: '../../vfm.png',
    moneyReceived: '1,175.76 EUR',
    received: '-7.64',
    ConversionCost: '',
    exchangeRate: '1.19854',
  },
  {
    img: '../../baoviet.png',
    moneyReceived: '1,194.12',
    received: '-7.64',
    ConversionCost: '',
    exchangeRate: '1.19854',
    title: ""
  },
])

</script>

<style lang="scss" scoped>

</style>
