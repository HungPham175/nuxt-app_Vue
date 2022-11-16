<template>
  <div class="bg-sale">
    <div class=" border-2 text-[#FFD530] flex justify-between items-center flex-wrap">
      <div class="">
        <div>
          <p class="text-[34px] font-bold ">Khuyến mãi hiện tại</p>
        </div>
        <div>
          <img src="../../public/all-new.png" />
        </div>
        <div>
          <button class="bg-btn rounded-6 py-2 px-4 outline-0 border-0 bg-yellow">Xem chi tiết
            <img src="../../public/arrow-right.svg" />
          </button>
        </div>
        <!-- <div > 
          <span class="bg-yellow-400 rounded-l-2/4 p-3"> </span>
          <span class="bg-yellow-400 rounded-r-2/4 p-3">-></span>
        </div> -->
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
