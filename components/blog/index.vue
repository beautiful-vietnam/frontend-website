<template>
  <section class="wrap-blog container">
    <h2 class="title">
      Chia sẻ bài viết trên nhóm
    </h2>
    <div class="wrap-image">
      <b-row>
        <b-col>
          <div class="card">
            <img
              class="card-img-top"
              src="/img/blog1.png"
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
        <b-col>
          <div class="card">
            <img
              class="card-img-top"
              src="/img/blog2.png"
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
        <b-col>
          <div class="card">
            <img
              class="card-img-top"
              src="/img/blog3.png"
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
      <b-row class="row2">
        <b-col>
          <div class="card">
            <img
              class="card-img-top"
              src="/img/blog4.png"
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
        <b-col>
          <div class="card">
            <img
              class="card-img-top"
              src="/img/blog5.png"
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
        <b-col>
          <div class="card">
            <img
              class="card-img-top"
              src="/img/blog6.png"
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
</style>
