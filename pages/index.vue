<template>
    <div class="w-19/20 max-w-[1200px] mx-auto font-sans">
        <Nav />
        <div class=""> </div>
        <div class="flex md:justify-between lt-md:flex-col relative z-1">
            <Content />
            <MoneyLeft />
        </div>
        <div class="relative z-8">
            <!-- <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-sky-400 opacity-75"></span> -->
            <img src="../public/message.png" class="w-[12rem] lt-md:w-[9rem] fixed bottom--6 right-0 z-99  " />
        </div>
        <!-- dùng tranform 50/50  -->
        <div class="lt-md:hidden absolute top-[8rem] right-[40rem] z-0">
            <img src="../public/Ellipse2.png" alt="" class="blur-[150px]">
        </div>
        <div class="relative lt-md:top-[12rem]">
            <Message />
        </div>
        <div class="lt-md:pt-[15rem]">
            <MainTable />

        </div>
        <div class="pt-[10rem] lt-md:pt-[2rem]">
            <MainSale />
        </div>
    </div>

</template>
<script>


</script>
<style>
.top--6 {
    top: -6rem;
}

.btn-c {
    bottom: 20px;
    right: 30px;
    z-index: 99;
    cursor: pointer;
}

</style>