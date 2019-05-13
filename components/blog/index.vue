<template>
  <section class="wrap-blog container">
    <h2 class="title">
      Chia sẻ bài viết trên nhóm
    </h2>
    <div class="wrap-image">
      <b-row>
        <b-col cols="12" sm="4">
          <div class="card">
            <img
              class="card-img-top"
              src="../../assets/img/blog1.png"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5 class="card-title">Hà Nội</h5>
              <p class="card-text">
                Thành phố Hà Nội là Thủ đô ngàn năm văn hiến với những di tích
                cổ xưa, cuộc sống yên bình...
              </p>
              <a href="#" class="btn btn-primary button">XEM THÊM</a>
            </div>
          </div>
        </b-col>
        <b-col cols="12" sm="4">
          <div class="card">
            <img
              class="card-img-top"
              src="../../assets/img/blog2.png"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5 class="card-title">Đà Nẵng</h5>
              <p class="card-text">
                Đà Nẵng là một thành phố trực thuộc trung ương, nằm trong vùng
                Nam Trung Bộ, Việt Nam...
              </p>
              <a href="#" class="btn btn-primary button">XEM THÊM</a>
            </div>
          </div>
        </b-col>
        <b-col cols="12" sm="4">
          <div class="card">
            <img
              class="card-img-top"
              src="../../assets/img/blog3.png"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5 class="card-title">Thừa thiên - Huế</h5>
              <p class="card-text">
                Thừa Thiên - Huế là một tỉnh ven biển nằm ở vùng Bắc Trung Bộ
                Việt Nam có tọa độ ở ...
              </p>
              <a href="#" class="btn btn-primary button">XEM THÊM</a>
            </div>
          </div>
        </b-col>
      </b-row>
      <b-row class="row2" cols="12" sm="4">
        <b-col>
          <div class="card">
            <img
              class="card-img-top"
              src="../../assets/img/blog4.png"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5 class="card-title">Ninh Bình</h5>
              <p class="card-text">
                Ninh Bình thuộc khu vực đồng bằng sông Hồng dù chỉ có 2 huyện
                duyên hải là Yên Khánh ...
              </p>
              <a href="#" class="btn btn-primary button">XEM THÊM</a>
            </div>
          </div>
        </b-col>
        <b-col cols="12" sm="4">
          <div class="card">
            <img
              class="card-img-top"
              src="../../assets/img/blog5.png"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5 class="card-title">Hồ Chí Minh</h5>
              <p class="card-text">
                Thành phố Hồ Chí Minh là thành phố lớn nhất Việt Nam, đồng thời
                cũng là một trong những ...
              </p>
              <a href="#" class="btn btn-primary button">XEM THÊM</a>
            </div>
          </div>
        </b-col>
        <b-col cols="12" sm="4">
          <div class="card">
            <img
              class="card-img-top"
              src="../../assets/img/blog6.png"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5 class="card-title">Hà Giang</h5>
              <p class="card-text">
                Hà Giang phía đông giáp tỉnh Cao Bằng, phía tây giáp tỉnh Yên
                Bái và Lào Cai, phía nam giáp tỉnh ...
              </p>
              <a href="#" class="btn btn-primary button">XEM THÊM</a>
            </div>
          </div>
        </b-col>
      </b-row>
    </div>
  </section>
</template>

<style lang="scss" scoped>
$color-primary: #a41c66;

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
      border-bottom: 2px solid $color-primary;
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
    height: auto;
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
      background: $color-primary;
      border: $color-primary;
    }
  }
}

@media (max-width: 576px) {
  .wrap-blog {
    margin-top: 2rem;
    .title {
      font-size: 1.5rem;
    }
    .button {
      font-size: 0.9rem;
      margin-bottom: 1rem;
    }
    .card {
      width: 100%;
    }
  }
}
</style>
