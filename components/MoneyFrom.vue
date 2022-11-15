<template>
    <div class="bg-transparent flex justify-center items-center md:w-281 w-238 lt-md:absolute lt-md:top-15">
        <div class="bg-shadow-blur backdrop-blur-[50px] md:w-281 w-238 p-8 lt-md:p-5 lt-md:p-4  border border-white rounded-12 md:absolute md:top-[3.4rem]">
            <div class="pb-6">
                <ButtonMoney />
            </div>
            <div class="flex justify-between pb-6">
                <div>
                    <li>Lệ phí</li>
                </div>
                <div class="text-14">
                    <span class="text-gray-400 line-through">! 6AUD</span> 3AUD
                    <div class="text-18 text-xanhla">Giảm 50% phí </div>
                </div>
            </div>
            <div class="flex-between pb-6">
                <div>
                    <li>Tỉ giá</li>
                </div>
                <div class="font-bold">1 AUD = 17.900 VND</div>
            </div>
            <div class="flex-between items-end pb-6">
                <div>
                    <li> Tỉ lệ đảm bảo</li>
                </div>
                <div>
                    1.20633 <img src="../public/chart.svg" class="w-2/6"/>
                </div>
            </div>
            <div class="pb-6">
                <ButtonMoney />
            </div>
            <div class="flex text-center pb-12">
                <p class="span-center basis-2/4 border-r"><span class="font-bold">Tiết kiệm</span><br />21.29 GPA</p>
                <p class="span-center basis-2/4"><span class="font-bold">Vận chuyển </span> <br />trong 4 giờ </p>
            </div>
            <div class="font-bold flex justify-between">
                <p>
                    Tổng cộng:
                </p>
                <p>100.000.000 AUD</p>
            </div>
            <div class="pt-6 flex justify-end">
                <button class="btn bg-yellow-btn py-3 rounded-12 p-12 shadows-yellow ">Chuyển tiền</button>
            </div>
        </div>
        <div class="h-"></div>
    </div>
</template>

<script>
export default {

}
</script>
<style>
.flex-between {
    display: flex;
    justify-content: space-between;
}
.bg-yellow-btn{
    background-color: #FFD530 !important;
}
.shadows-yellow{
   box-shadow: 4px 8px 48px rgba(255, 220, 94, 0.8)
}
.text-18{
    font-size: 18px;
}
.text-14{
    font-size: 14px !important;
}
.text-xanhla{
    color: #4AE800;
}
/* blur */
.w-281 {
    width: 28.125rem;
}

.w-238 {
    width: 20.875rem !important;
}
top-34{
    top:3.4rem;
}
.bg-shadow-blur{
    box-shadow: 4px 8px 48px rgba(0, 0, 0, 0.05);
}

</style>