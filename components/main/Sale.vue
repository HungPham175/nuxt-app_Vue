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
        <div class="w-full">
          <!-- <button class="bg-btn rounded-6 py-2 px-4 outline-0 border-0 bg-yellow">Xem chi tiết
            <img src="../../public/arrow-right.svg" />
          </button> -->
          <!-- <div class="w-10 h-10 rounded-2/4 bg-yellow-200 flex justify-center items-center text-black text-center hover:w-20 hover:rounded-2/100"> 
            <span class="">-> </span>
            <span class="bg-yellow-400 rounded-r-2/4 h-10 w-10"></span>
          </div> -->
          <div class="flex items-center hidden md-block h-0" role="none">
            <a href="/insider" class="w-12 h-12 min-w-1 
                trans relative justify-center items-center outline-0 whitespace-nowrap 
                flex-nowrap rounded-full ml-5 text-yellow
                backface-visibility translate-0 no-underline decoration-inherit" aria-label="Insider">
              <span style="transform: matrix(1, 0, 0, 1, 0, 0);" class="
                    border-y-2 border-yellow border-l-2 rounded-tl-12 rounded-bl-12
                    min-w-6 absolute top-0 left-0 z-1 h-12 left-0 will-unset ">
              </span>
              <span class="h-12 border-yellow will-unset absolute -right-2/4 top-0 
                     trans-center overflow-hidden"
                style="width: 106px; transform: translate(-100%, 0%) matrix(0.01, 0, 0, 1, 0, 0); transform-origin: 100% 0px 0px; background-color: rgba(0,0,0,.001);">
              </span>
              <span class="
                           w-11/5  h-12 absolute right-[24px] top-0 z-2 flex items-center overflow-hidden 
                           pr-[30px] pl-[10px] pointer-events-none trans-lable will-opacity"
                style="visibility: hidden; opacity: 0; transform: matrix(1, 0, 0, 1, 0, 0);">
                <span class=""
                  style="transform: translate(100%, 0%) matrix(1, 0, 0, 1, 0, 0); transform-origin: 100% 0px 0px;">Insider</span>
              </span>

              <svg aria-hidden="true" class="icon see-more__icon icon-arrow -ml-[11px]
                                              text-yellow absolute top-2/4 left-2/4 z-5 w-8 h-8
                                              overflow-hidden vertical-align: middle;"
                style="transform: matrix(1, 0, 0, 1, 0, -16);">
                <use xlink:href="#icon-arrow" href="#icon-arrow"></use>
              </svg>

              <span class="see-more__right h-12 border-yellow border min-w-6" style="background-color:rgba(0,0,0,.001);transform: matrix(1, 0, 0, 1, 0, 0);"></span>
    border-color: #f0b12f;
    will-change: unset;
            </a>
          </div>
        </div>
      </div>
      <div class="absolute bottom-0 right-3 w-2/5 ">/insider
        <img src="../../public/SaleGirl.png" class="max-w-full " />
      </div>
      <div class="absolute bottom-0 z--12 lt-md:w-full">
        <img src="../../public/bg-sale.png" class="max-w-full w-full lt-md:h-[7rem]" />
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

.trans {
  transition: transform .3s cubic-bezier(.215, .61, .355, 1);
}

.backface-visibility {
  backface-visibility: hidden;
}

.will-unset {
  will-change: unset;
}

.trans-center {
  transition: background-color .4s cubic-bezier(.215, .61, .355, 1);
}

.trans-lable {
  transition: width .65s cubic-bezier(.215, .61, .355, 1);
}

.will-opacity {
  will-change: opacity;
}

.trans-inner {
  transform: translate(100%, 0%) matrix(1, 0, 0, 1, 0, 0);
}
</style>
