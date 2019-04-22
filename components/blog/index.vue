<template>
  <section class="wrap-blog container">
    <h2 class="title">
      Chia sẻ bài viết trên nhóm
    </h2>
    <div class="wrap-image">
        <b-row>
            <b-col>
                <div class="card">
                  <img class="card-img-top" src="/img/blog1.png" alt="Card image cap">
                  <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content...</p>
                    <a href="#" class="btn btn-primary button">XEM THÊM</a>
                  </div>
                </div>
            </b-col>
            <b-col>
                <div class="card">
                  <img class="card-img-top" src="/img/blog2.png" alt="Card image cap">
                  <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content...</p>
                    <a href="#" class="btn btn-primary button">XEM THÊM</a>
                  </div>
                </div>
            </b-col>
            <b-col>
                <div class="card">
                  <img class="card-img-top" src="/img/blog3.png" alt="Card image cap">
                  <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content...</p>
                    <a href="#" class="btn btn-primary button">XEM THÊM</a>
                  </div>
                </div>
            </b-col>
        </b-row>
        <b-row class="row2">
            <b-col>
                <div class="card">
                  <img class="card-img-top" src="/img/blog4.png" alt="Card image cap">
                  <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content...</p>
                    <a href="#" class="btn btn-primary button">XEM THÊM</a>
                  </div>
                </div>
            </b-col>
            <b-col>
                <div class="card">
                  <img class="card-img-top" src="/img/blog5.png" alt="Card image cap">
                  <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content...</p>
                    <a href="#" class="btn btn-primary button">XEM THÊM</a>
                  </div>
                </div>
            </b-col>
            <b-col>
                <div class="card">
                  <img class="card-img-top" src="/img/blog6.png" alt="Card image cap">
                  <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content...</p>
                    <a href="#" class="btn btn-primary button">XEM THÊM</a>
                  </div>
                </div>
            </b-col>
        </b-row>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.wrap-blog {
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
}

.wrap-image {
    clear: both;
    padding-top: 2rem;
    .row2 {
        margin-top: 2rem;
    }
}
.card {
    border: 0;
    width: 90%;
    .card-img-top {
        border-radius: 0;
        width: 100%;
        height: 240px;
    }
    .card-body {
        padding: 0;
        .card-title {
            width: 100%;
            margin-top: -40px;
            color: white;
            height: 40px;
            line-height: 40px;
            padding-left: 10px;
            background: #000000b3;
            font-weight: 400;
        }
        .card-text {
            letter-spacing: -0.4px;
        }
        .button {
            border-radius: 0;
        }
    }
}
</style>
