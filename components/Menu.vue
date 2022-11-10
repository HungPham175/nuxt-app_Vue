<template >
    <div class="flex items-center h-[91px]">
        <div class="">
            <img src="../public/Frame.svg" alt="Logo" class="w-[228px] lt-md:w-[150px]">
        </div>
        <div class="flex justify-between">
       
        <ButtonRespon v-on:click="toggleNavbar()"/>
        <div>
        <div class="flex gap-4"  id="navbar-default">
            <a class="no-underline text-black" href="#">Trang chủ
                <hr class="border-1 border-yellow w-2/4" />
            </a>
            <a class="no-underline text-black" href="#">Chuyển tiền</a>
            <a class="no-underline text-black" href="#">Về chúng tôi</a>
        </div>
        <div class="flex gap-3">
            <button class="rounded-full w-30 p-3.5 border-1 bg-white hover:text-yellow hover:bg-indigo-900"> Đăng
                Nhập</button>
            <button
                class="rounded-full w-30 p-3.5 border-0 text-yellow bg-indigo-900 hover:border hover:bg-indigo-700 border-1">
                Đăng Ký</button>
            <select class="border-0 w-16 text-2xl">
                <option value="Vn">🇻🇳</option>
                <option value="JP">🇯🇵</option>
            </select>
        </div>
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
    toggleNavbar: function(){
      this.showMenu = !this.showMenu;
    }
  }
}
</script>
<style >

</style>