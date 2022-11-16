<template>
  <div class="md:pt-6">
    <div class="font-semibold text-xl py-3">
      <p class="lt-md:text-sm">So sánh tỷ giá</p>
      <p class="text-[34px] lt-md:text-xl">Tỷ giá chuyển đổi tốt nhất thị trường không có phụ phí</p>
    </div>
    <div class="p-12 table-items lt-md:p-4">
      <div>
        <div class="text-end grid grid-cols-4 lt-md:grid-cols-2  md:text-xl font-semibold p-7 lt-md:p-4 lt-md:text-sm">
          <div class="lt-md:text-start">Gửi 1,000,000 GBP với</div>
          <div>Tiền thực nhận<br /><span class="text-sm font-none lt-md:text-center">(Tổng chi phí sau thuế)</span>
          </div>
          <div class="lt-md:hidden">Chi phí chuyển đổi</div>
          <div class="lt-md:hidden">Tỷ giá chuyển đổi<br /><span class="font-none text-sm">( 1GBP -> EUR )</span></div>
        </div>
        <MainDefaultFirst />
        <MainTableFor />
      </div>

    </div>
    <div class="lt-md:hidden flex justify-between py-12">
        <li class="w-2/5 font-semibold text-xl">Không có phí ẩn</li>
        <p class="text-basic">Từ giờ trở đi, bạn có thể nhận tiền gửi ngân hàng một cách an toàn và bảo mật từ Hoa kỳ qua số thẻ ghi nợ Visa của mình. Trong thời gian có hạn, người gửi của bạn sẽ nhận được ưu đãi đặc biệt khi gửi tiền đến thẻ ghi nợ Visa qua “CHUYỂN TIỀN TIẾT KIỆM” Visa qua “CHUYỂN TIỀN TIẾT KIỆM”Visa qua “CHUYỂN TIỀN TIẾT KIỆM”.</p>
    </div>
  </div>
</template>
<script setup lang="ts">

</script>
<style>
.table-grid {
  justify-content: flex-end;
}

.bg-light-purple {
  background-color: #EBF0FF;
}

.table-items {
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid #FFFFFF;
  box-shadow: 4px 8px 84px rgba(0, 0, 0, 0.05);
  backdrop-filter: blur(150px);
  border-radius: 24px;
}

.font-none {
  font-weight: normal !important;
}
</style>