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
          Discover Amazing places in Japan
        </h1>
        <p class="description">
          Jump off balcony, onto stranger's head. Chase ball of string hide when
          guests come over. Being gorgeous with belly side up i could pee on
          this if i had the energy but under the bed, for attack the child, open
          the door,
        </p>
        <div class="wrap-search">
          <b-input-group class="mb-2 mr-sm-2 mb-sm-0">
            <b-input
              class="custom-input"
              placeholder="What would you like to do?"
            ></b-input>
            <b-input
              class="custom-input"
              placeholder="Where would you like to go?"
            ></b-input>
            <b-button class="button-search">SEARCH</b-button>
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
  font-family: Lato;
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
        font-weight: 500;
        font-size: 1.2rem;
        font-family: Lato;
      }
    }
    .button-search {
      border-radius: 0;
      background: #1b7dff;
      border: 0;
      width: 125px;
      letter-spacing: 1px;
    }
  }
}
</style>
