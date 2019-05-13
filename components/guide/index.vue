<template>
  <section class="container wrap-guide">
    <h2 class="title">
      Beautiful Viet Nam
    </h2>
    <b-row class="wrap-content">
      <b-col cols="12" sm="4" class="one-guide">
        <img src="../../assets/img/icon1.png" alt="icon instagram" class="icon" />
        <div>
          <p class="title-content">
            Instagram
          </p>
          <p class="content">
            Chia sẻ những hình ảnh và video lưu lại khoảnh khắc tuyệt vời của
            bạn khi đi du lịch ở Việt Nam.
          </p>
          <a
            href="https://www.instagram.com/beautiful_viet_nam/"
            target="_blank"
            class="read-more"
            >Xem thêm</a
          >
        </div>
      </b-col>
      <b-col cols="12" sm="4" class="one-guide">
        <img src="../../assets/img/icon3.png" alt="icon fanpage" class="icon" />
        <div>
          <p class="title-content">
            Fanpage
          </p>
          <p class="content">
            Trang chia sẻ tin tức, thông tin về ngành du lịch trong nước cập
            nhật liên tục hàng ngày hàng giờ..
          </p>
          <a
            href="https://facebook.com/beautiful.vietnam.official/"
            target="_blank"
            class="read-more"
            >Xem thêm</a
          >
        </div>
      </b-col>
      <b-col cols="12" sm="4" class="one-guide">
        <img src="../../assets/img/icon2.png" alt="icon group" class="icon" />
        <div>
          <p class="title-content">
            Nhóm Facebook
          </p>
          <p class="content">
            Nhóm chia sẻ những kinh nghiệm, hỏi đáp, tìm người đi du lịch cùng
            bạn trên khắp mọi miền đất nước.
          </p>
          <a
            href="https://www.facebook.com/groups/312995652676992/"
            target="_blank"
            class="read-more"
            >Xem thêm</a
          >
        </div>
      </b-col>
    </b-row>
  </section>
</template>

<style lang="scss" scoped>
.wrap-guide {
  margin-top: -12rem;
  background: #fff;
  padding: 5rem 4.5rem 7rem 4.5rem;
  box-shadow: 0px 2px 20px rgba(21, 24, 36, 0.15993);
  .title {
    font-weight: 500;
    font-size: 2rem;
    line-height: 42px;
  }
  .wrap-content {
    margin-top: 4.5rem;
    .icon {
      width: 65px;
    }
    .title-content {
      margin-top: 2rem;
      font-weight: 500;
      font-size: 1.125rem;
      line-height: 24px;
      color: #000000;
    }
    .content {
      margin-bottom: 2.5rem;
    }
    .read-more {
      &:after {
        content: '';
        background: url('../../assets/img/arrow.png') no-repeat;
        height: 8px;
        width: 33px;
        display: inline-block;
        margin: 0 0 2px 12px;
      }
    }
  }
}

@media (max-width: 576px) {
  .one-guide {
    display: flex;
    margin-bottom: 10px;
  }
  .icon {
    width: 50px !important;
    height: 50px;
    margin-right: 15px;
    margin-top: 4px;
  }
  .title-content {
    margin: 0 !important;
    font-size: 1rem !important;
  }
  .content {
    margin: 0 !important;
  }
  .read-more {
    font-size: 0.9rem;
  }
  .wrap-content {
    margin-top: 1rem !important;
  }
  .wrap-guide {
    padding: 2rem 1rem 2rem 1rem;
    .title {
      font-size: 1.5rem;
      text-align: center;
    }
  }
}
</style>
