<template>
    <div class="">
    <div class="backdrop-blur-[42px] w-[450px] lt-md:w-[230px]
        p-8 rounded-6 border-white border-2 absolute top-[61px] left-[100px] 
        lt-md:items-center lt-md:left-[25px] lt-md:top-[80px] lt-md:p-4
        ">
        <form action="#" class="bg-transparent">
            <div class="flex">
                <div class="bg-white flex-initial px-2 py-1 w-[80%] rounded-l-[8px] lt-md:w-[60%] ">
                    <label class="lt-md:text-[14px]"> Số tiền gửi</label>
                    <br>
                    <input type="text" name="moneyUp" id="moneyUp"
                        class="border-0 outline-0 text-[20px] p-0  m-0 lt-md:text-[16px] lt-md:mt-2 lt-md:font-bold">
                </div>
                <button class="bg-[#7fb2ff] border-0 flex-initial w-[20%] rounded-r-[8px] lt-md:w-[40%] text-">
                    <select class="bg-transparent border-0 text-white">
                        <option value="VN">🇻🇳 VN</option>
                        <option option value="VO">🇺🇸 VO</option>
                    </select>
                </button>
            </div>
            <div class="py-6 lt-md:text-[12px]">
                <div class="flex justify-between ]">
                    <li>Le phi:</li>
                    <p class="m-0 p-0 l">
                        <span class="text-gray-400 line-through ">!6 AUD</span>
                        <span class="pl-6">3 AUD</span>
                        <br>
                        <i class="text-[#4AE800]">Giảm 50% lệ phí</i>
                    </p>
                </div>
                <div class="flex justify-between pt-[24px]">
                    <li>Tỉ giá:</li>
                    <p class="m-0 p-0 text-[20] font-semibold">
                        1 AUD = 16,900 VND
                    </p>
                </div>
                <div class="flex justify-between pt-[24px]">
                    <li class="flex items-center">
                    <li></li> Tỉ lệ đảm bảo:</li>
                    <p class="m-0 p-0 flex justify-center items-center">
                        1.20633
                        <img src="../public/chart.svg">
                    </p>
                </div>

                <div class="flex py-[24px]">
                    <div class="bg-white flex-initial p-3 w-[80%] rounded-l-[8px]">
                        <label class=""> Số tiền gửi</label>
                        <br>
                        <input type="text" name="moneyUp" id="moneyUp" class="border-0 outline-0 text-[20px]">
                    </div>
                    <button class="bg-[#7fb2ff] border-0 flex-initial w-[20%] rounded-r-[8px] w-[112px]">
                        <select class="bg-transparent border-0 text-white">
                            <option value="VN">🇻🇳 VN</option>
                            <option value="VO">🇺🇸 VO</option>
                        </select>
                    </button>
                </div>
                <div class="flex text-center text-[14px] lt-md:justify-between">
                    <p class="basis-1/2 border-r border-gray">
                        <span class="font-bold">Tiết kiệm</span>
                        <br>21.29 GPA
                    </p>
                    <p class="basis-1/2">
                        <span class="font-bold">Vận chuyển </span>
                        <br>Trong 4 giờ
                    </p>
                </div>
                <div class="text-[20px] font-semibold flex lt-md:text-[18px]">
                    <p class="basis-1/2">Tổng Cộng:</p>
                    <p class="basis-1/2">100.000.000 AUD</p>
                </div>
                <div class="flex flex-row-reverse">
                    <button
                        class="text-[16px] bg-[#ffd531] font-semibold py-[14px] px-[32px] rounded-16 border-0 outline-0 shadow-xl shadow-yellow-300">Chuyển
                        tiền</button>
                </div>
            </div>
        </form>
    </div>
</div>
</template>