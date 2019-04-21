<template>
  <section class="wrap-insta container">
    <h2 class="title">
      Hãy chia sẻ khoảnh khắc đẹp của bạn
    </h2>
    <a href="#" class="share">CHIA SẺ VỚI CHÚNG TÔI</a>
    <div class="wrap-image">
      <b-row>
        <b-col class="pr-1">
          <img src="/img/insta1.png" alt="ha noi" class="image-lg" />
          <p class="category">Hà Nội</p>
        </b-col>
        <b-col class="pl-1">
          <img src="/img/insta2.png" alt="da nang" class="image-lg" />
          <p class="category">Đà Nẵng</p>
        </b-col>
      </b-row>
      <b-row class="mt-2">
        <b-col class="pr-0">
          <img src="/img/insta3.png" alt="hue" class="image-sm" />
          <p class="category">Huế</p>
        </b-col>
        <b-col class="px-2">
          <img src="/img/insta4.png" alt="ninh binh" class="image-sm" />
          <p class="category">Ninh Bình</p>
        </b-col>
        <b-col class="pl-0">
          <img src="/img/insta5.png" alt="ha giang" class="image-sm" />
          <p class="category">Hà Giang</p>
        </b-col>
      </b-row>
    </div>
  </section>
</template>

<style lang="scss" scoped>
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
      border-bottom: 2px solid #006dfe;
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
    width: 364px;
  }
  .category {
    position: absolute;
    font-weight: bold;
    font-size: 2.7rem;
    line-height: 60px;
    margin-top: -80px;
    margin-left: 30px;
    color: #ffffffee;
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  }
}
</style>
