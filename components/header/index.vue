<template>
  <section class="wrap-header">
    <div class="container">
      <b-navbar toggleable="lg" type="dark">
        <b-navbar-brand href="#">
          <img src="/img/logo.png" alt="logo beautiful vietnam" />
        </b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="ml-auto">
            <b-navbar-nav>
              <b-nav-item href="#">Articles</b-nav-item>
              <b-nav-item href="#">Locations</b-nav-item>
              <b-nav-item href="#">Videos</b-nav-item>
              <b-nav-item href="#">Sign in</b-nav-item>
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
            <b-button class="button-search">TÌM KIẾM</b-button>
          </b-input-group>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.wrap-header {
  height: 125vh;
  background-image: url('/img/background.png');
  background-size: cover;
  .container {
    background: none;
    padding-top: 20px;
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
    color: rgb(207, 207, 207) !important;
  }
}
.wrap-content {
  .heading {
    font-weight: 400;
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
      background: url('/img/oval.png') no-repeat;
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
    }
    .button-search {
      font-weight: bold;
      border-radius: 0;
      background: #1b7dff;
      border: 0;
      width: 125px;
      letter-spacing: 1px;
    }
  }
}
</style>
