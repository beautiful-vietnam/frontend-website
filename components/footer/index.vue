<template>
  <footer class="wrap-footer">
    <div class="wrap-content container">
      <b-row>
        <b-col cols="12" sm="6" class="text-center">
          <img src="/img/logo-footer.png" alt="logo footer" class="logo" />
        </b-col>
        <b-col cols="12" sm="2">
          <ul class="list">
            <li class="connect">KẾT NÔI</li>
            <li>
              <a
                href="https://facebook.com/beautiful.vietnam.official/"
                class="text-footer"
                target="_blank"
                >Facebook</a
              >
            </li>
            <li>
              <a
                href="https://www.youtube.com/channel/UCx499tTpB3YTY9KUJgJ4XNQ"
                class="text-footer"
                target="_blank"
                >Youtube</a
              >
            </li>
            <li>
              <a
                href="https://www.facebook.com/groups/312995652676992/"
                class="text-footer"
                target="_blank"
                >Group</a
              >
            </li>
            <li>
              <a
                href="https://www.instagram.com/beautiful_viet_nam/"
                class="text-footer"
                target="_blank"
                >Instagram</a
              >
            </li>
          </ul>
        </b-col>
        <b-col cols="12" sm="4">
          <ul class="list">
            <li class="connect">LIÊN HỆ</li>
            <li>Email: beautiful.vietnam.official@gmail.com</li>
            <li>
              Địa chỉ: Tầng 4 - Hòa Bình Green City - 505 Minh Khai - Hai Bà
              Trưng - Hà Nội
            </li>
            <li>
              Developed by:
              <a href="https://sharpteam.netlify.com/" target="_blank"
                >Sharp Team</a
              >
            </li>
          </ul>
        </b-col>
      </b-row>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
$color-primary: #a41c66;

.wrap-footer {
  margin-top: 7rem;
  background: #0e1d28;
  .wrap-content {
    padding: 5rem 0;
    color: white;
    .list {
      list-style: none;
      font-weight: 300;
      .connect {
        font-weight: bold;
        margin-bottom: 1rem;
      }
    }
  }
}
.text-footer {
  color: white !important;
}
@media (max-width: 576px) {
  .wrap-content {
    padding: 2rem 0 !important;
  }
  .logo {
    width: 150px;
  }
}
</style>
