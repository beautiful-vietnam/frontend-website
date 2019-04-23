<template>
  <section class="wrap-intro container">
    <b-row>
      <b-col>
        <img
          src="/img/intro1.png"
          alt="gioi thieu ha noi"
          class="image-intro ma-3"
        />
      </b-col>
      <b-col class="pb-4 pt-2 px-5">
        <h3>Giới thiệu về Hà Nội</h3>
        <p class="description">
          Thành phố Hà Nội là Thủ đô ngàn năm văn hiến với những di tích cổ xưa,
          cuộc sống yên bình. Nếu đã một lần du lịch Hà Nội, chắc chắn bạn không
          thể nào quên không khí đặc trưng nơi đây, với Hồ Gươm, Hồ Tây, những
          quán cafe trầm mặc, những con đường nhỏ và những gánh hàng rong.
        </p>
        <a href="#" class="read-more">Xem thêm</a>
      </b-col>
    </b-row>
    <b-row class="mt-5">
      <b-col class="py-4 px-5">
        <h3>Giới thiệu về Đà Nẵng</h3>
        <p class="description">
          Đà Nẵng thành phố biển xinh đẹp hiền hòa và mếm khách, nơi mà bạn có
          thể dễ dàng đến được bằng cả đường bộ, đường hàng không và đường thủy.
          Một dấu ấn địa lý và lịch sử, điểm trung chuyển tiện lợi đến các di
          sản văn hóa thế giới như Huế, Mỹ Sơn, Hội An và khu dự trữ sinh quyển
          thế giới Cù Lao Chàm.
        </p>
        <a href="#" class="read-more">Xem thêm</a>
      </b-col>
      <b-col>
        <img
          src="/img/intro2.png"
          alt="gioi thieu da nang"
          class="image-intro"
        />
      </b-col>
    </b-row>
  </section>
</template>

<style lang="scss" scoped>
.wrap-intro {
  margin-top: 7rem;
}
.image-intro {
  width: 525px;
  height: 310px;
}
.description {
  margin-top: 2.5rem;
  letter-spacing: -0.5px;
}
.read-more {
  position: absolute;
  bottom: 15px;
  &:after {
    content: '';
    background: url('/img/arrow.png') no-repeat;
    height: 8px;
    width: 33px;
    display: inline-block;
    margin: 0 0 2px 12px;
  }
}
</style>
