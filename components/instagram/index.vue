<template>
  <section class="wrap-insta container">
    <h2 class="title">
      Hãy chia sẻ khoảnh khắc đẹp của bạn
    </h2>
    <a href="#" class="share">CHIA SẺ VỚI CHÚNG TÔI</a>
    <div class="wrap-image">
      <b-row class="mx-0">
        <b-col class="px-0" sm="12" lg="6">
          <img src="/img/insta1.png" alt="ha noi" class="image-lg" />
          <p class="category">Hà Nội</p>
        </b-col>
        <b-col class="px-0" sm="12" lg="6">
          <img src="/img/insta2.png" alt="da nang" class="image-lg" />
          <p class="category">Đà Nẵng</p>
        </b-col>
      </b-row>
      <b-row class="mx-0 mt-1">
        <b-col class="px-0" sm="12" lg="4">
          <img src="/img/insta3.png" alt="hue" class="image-sm mt-remove" />
          <p class="category">Huế</p>
        </b-col>
        <b-col class="px-0" sm="12" lg="4">
          <img src="/img/insta4.png" alt="ninh binh" class="image-sm" />
          <p class="category">Ninh Bình</p>
        </b-col>
        <b-col class="px-0" sm="12" lg="4">
          <img src="/img/insta5.png" alt="ha giang" class="image-sm" />
          <p class="category">Hà Giang</p>
        </b-col>
      </b-row>
    </div>
  </section>
</template>

<style lang="scss" scoped>
$color-primary: #a41c66;

.wrap-insta {
  margin-top: 7rem;
  .title {
    float: left;
    font-size: 2rem;
    line-height: 42px;
    color: #102746;
    &:after {
      content: '';
      width: 250px;
      border-bottom: 2px solid $color-primary;
      display: block;
      margin-top: 4px;
    }
  }
  .share {
    float: right;
    &:after {
      content: '';
      background: url('/img/arrow.png') no-repeat;
      height: 8px;
      width: 33px;
      display: inline-block;
      margin: 0 0 2px 12px;
    }
  }
}
.wrap-image {
  clear: both;
  padding-top: 2rem;
  cursor: pointer;
  .image-lg {
    width: 551px;
    height: 330px;
  }
  .image-sm {
    height: 250px;
    width: 365px;
  }
  .category {
    position: absolute;
    font-weight: bold;
    font-size: 2rem;
    line-height: 60px;
    margin-top: -80px;
    margin-left: 30px;
    color: #ffffffee;
    text-shadow: 0px 4px 4px #000;
  }
}

@media (max-width: 992px) {
  .image-lg {
    width: 100% !important;
    height: auto !important;
    &:nth-child(1) {
      margin-top: 5px;
    }
  }
  .image-sm {
    width: 100% !important;
    height: auto !important;
    &:nth-child(1) {
      margin-top: 5px;
    }
  }
  .mt-remove {
    margin-top: 0 !important;
  }
}
</style>
