<template>
  <section class="wrap-header">
    <div class="container">
      <b-navbar toggleable="lg" type="dark">
        <b-navbar-brand href="#">
          <img src="../../assets/img/logo.png" alt="logo beautiful vietnam" class="logo" />
        </b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="ml-auto">
            <b-navbar-nav>
              <b-nav-item
                href="https://facebook.com/beautiful.vietnam.official/"
                target="_blank"
                >Fanpage</b-nav-item
              >
              <b-nav-item
                href="https://www.youtube.com/channel/UCx499tTpB3YTY9KUJgJ4XNQ"
                target="_blank"
                >Youtube</b-nav-item
              >
              <b-nav-item
                href="https://www.instagram.com/beautiful_viet_nam/"
                target="_blank"
                >Instagram</b-nav-item
              >
              <b-nav-item
                href="https://www.facebook.com/groups/312995652676992/"
                target="_blank"
                >Group Facebook</b-nav-item
              >
            </b-navbar-nav>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
      <div class="wrap-content">
        <h1 class="heading">
          Khám phá những địa điểm tuyệt vời ở Việt Nam
        </h1>
        <p class="description">
          Bạn còn trẻ, xăng còn rẻ, đôi chân còn khỏe. Một lần trong đời, hãy
          xách ba lô lên và đi, tìm kiếm cho mình những niềm vui và trải nghiệm
          mới, đừng sợ mệt, đừng sợ ngày mai, đừng ngại không có tiền.
        </p>
        <div class="wrap-search">
          <b-input-group class="mb-2 mr-sm-2 mb-sm-0">
            <b-input
              class="custom-input"
              placeholder="Bạn thích làm gì?"
            ></b-input>
            <b-input
              class="custom-input"
              placeholder="Bạn muốn đi đâu?"
            ></b-input>
            <b-button class="button-search" @click="notification"
              >TÌM KIẾM</b-button
            >
          </b-input-group>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    notification() {
      alert('Tính năng đang phát triển!!!')
    }
  }
}
</script>

<style lang="scss" scoped>
$color-primary: #a41c66;

.wrap-header {
  height: 910px;
  background-image: url('../../assets/img/background.png');
  background-size: cover;
  .container {
    background: none;
    padding-top: 20px;
    .logo {
      width: 125px;
    }
  }
}
.nav-link {
  font-style: normal;
  font-weight: normal;
  font-size: 17px;
  line-height: 24px;
  color: #ffffff !important;
  padding-left: 2rem !important;
  padding-right: 2rem !important;
  &:hover {
    color: $color-primary !important;
  }
}
.wrap-content {
  .heading {
    font-weight: 500;
    font-size: 3rem;
    color: #ffffff;
    margin-top: 8rem;
    max-width: 570px;
  }
  .description {
    margin-top: 1.25rem;
    color: #ffffff;
    max-width: 540px;
  }
  .wrap-search {
    max-width: 850px;
    margin-top: 3.5rem;
    .custom-input {
      background: url('../../assets/img/oval.png') no-repeat;
      background-position: 0 2px;
      padding: 12px 0 30px 40px;
      border-radius: 0;
      margin-right: 80px;
      border-top: 0;
      border-right: 0;
      border-left: 0;
      &::placeholder {
        color: #fff;
        font-size: 1.2rem;
      }
      &:focus {
        -webkit-box-shadow: none;
        box-shadow: none;
        color: #fff;
      }
    }
    .button-search {
      font-weight: bold;
      border-radius: 0;
      background: $color-primary;
      border: 0;
      width: 125px;
      letter-spacing: 1px;
    }
  }
}

@media (max-width: 576px) {
  .wrap-header {
    height: 750px;
    .wrap-search {
      margin-top: 2rem;
    }
    .button-search {
      font-size: 14px;
    }
  }
  .heading {
    font-size: 1.7rem !important;
    margin-top: 3rem !important;
  }
  .custom-input {
    width: 100%;
    padding: 0 0 5px 25px !important;
    margin-right: 0 !important;
    background-size: 15px 15px !important;
    height: 25px;
    &::placeholder {
      font-size: 0.9rem !important;
    }
    &:nth-child(2) {
      margin-top: 10px;
      margin-bottom: 30px;
    }
  }
}
</style>
