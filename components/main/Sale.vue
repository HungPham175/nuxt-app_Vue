<template>
  <div class="relative">
    <div class="text-[#FFD530]">
      <div class="lt-md:h-full p-6 lt-md:p-4 flex flex-col gap-3">
        <div>
          <p class="text-[3vw] lt:text-[3vw] font-bold ">Khuyến mãi hiện tại</p>
        </div>
        <div>
          <img src="../../public/all-new.png" class="lt-md:w-1/3" />
        </div>
        <div>
          <!-- <button class="bg-btn rounded-6 py-2 px-4 outline-0 border-0 bg-yellow">Xem chi tiết
            <img src="../../public/arrow-right.svg" />
          </button> -->
          <div > 
            <span class="bg-yellow-400 rounded-l-2/4 p-3"> </span>
            <span class="bg-yellow-400 rounded-r-2/4 p-3">-></span>
          </div>
        </div>
      </div>
      <div class="absolute bottom-0 right-3 w-2/5 ">
        <img src="../../public/SaleGirl.png" class="max-w-full "/>
      </div>
      <div class="absolute bottom-0 z--12 lt-md:w-full">
        <img src="../../public/bg-sale.png" class="max-w-full w-full lt-md:h-[7rem]"/>
      </div>
      
    </div>
  </div>

</template>

<script lang="ts">
</script>

<style >
.bg-sale {
  background: url("../../public/bg-sale.png");
}
  
.bg-btn {
  box-shadow: 4px 8px 48px rgba(255, 255, 255, 0.25);
  backdrop-filter: blur(42px);
}
</style>
