<template>
  <div class="">
    <div class="">
      <p>So sánh tỷ giá</p>
      <p>Tỷ giá chuyển đổi tốt nhất thị trường không có phụ phí</p>
    </div>
    <div>
      <div class="text-end grid grid-cols-4 items-center">
        <div>Gửi 1,000,000 GBP với</div>
        <div>Tiền thực nhận<br/>(Tổng chi phí sau thuế)</div>
        <div class="lt-md:hidden">Chi phí chuyển đổi</div>
        <div class="lt-md:hidden">Tỷ giá chuyển đổi<br/>( 1GBP -> EUR )</div>

      </div>

    </div>
  </div>
</template>
<script setup lang="ts">
  import {ref} from "#imports";

   let Lists = ref([
    {
        img           : '../../public/Frame.svg',
        moneyReceived : '1,194.12 EUR',
        ConversionCost: '3.69 GBP',
        exchangeRate  : '1.19854',
    },
     {
       img           : '../../public/vfm.png',
       moneyReceived : '1,194.12 EUR',
       ConversionCost: '3.69 GBP',
       exchangeRate  : '1.19854',
     },
     {
       img           : '../../public/dragon.png',
       moneyReceived : '1,194.12 EUR',
       ConversionCost: '3.69 GBP',
       exchangeRate  : '1.19854',
     },
   ])

</script>
<style lang="">
    .table-grid{
      justify-content: flex-end
    }
</style>