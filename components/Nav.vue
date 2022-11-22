<template>
  <div class="flex items-center h-[91px] relative">
    <div class="w-35/100">
      <a href="#">
        <img src="../public/Frame.svg" class="lt-md:w-[150px]" />
      </a>
    </div>
    <ButtonRespon v-on:click="toggleNavbar()" />
    <div class="flex justify-between w-[75%]" :class="showMenu ? 'flex' : 'lt-md:hidden'" id="navbar-default">
      <div class="flex basic-2/4 items-center gap-6 relative">
        <a class="no-underline text-black hover:border-yellow hover:border-b-2 p-2" href="#">Trang chủ</a>
        <a class="no-underline text-black hover:border-yellow hover:border-b-2 p-2" href="#">Chuyển tiền</a>
        <a class="no-underline text-black hover:border-yellow hover:border-b-2 p-2" href="#">Về chúng tôi</a>
      </div>

      <div class="flex basic-2/4 gap-6">
        <button class="cursor-pointer rounded-full w-30 p-3.5 border-1 bg-white hover:text-yellow hover:bg-indigo-900"> Đăng
          Nhập</button>
        <button
          class="cursor-pointer rounded-full w-30 p-3.5 border-0 text-yellow bg-indigo-900 hover:border hover:bg-indigo-700 border-1">
          Đăng Ký</button>
        <select class="border-0 w-16 text-2xl">
          <option value="Vn">🇻🇳</option>
          <option value="JP">🇯🇵</option>
        </select>
      </div>
    </div>
  </div>
  <hr class="border-t-gray-[#414042] opacity-25 p-0 m-0" />
</template>

<script>
export default {
  data() {
    return {
      showMenu: false
    }
  },
  methods: {
    toggleNavbar: function () {
      this.showMenu = !this.showMenu;
    }
  }
}

</script>

<style lang="scss" scoped>

</style>
