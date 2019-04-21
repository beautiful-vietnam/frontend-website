<template>
  <section class="wrap-video container">
    <div class="wrap-content">
      <div class="video-tile -first">
        <img
          src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/39255/kf_glacier_1.jpg"
        />
        <video
          src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/39255/kf_glacier_1.mp4"
          preload="auto"
          loop="true"
        ></video>
      </div>
      <div class="video-toggle">
        <div class="video-toggle-inner">
          <video
            src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/39255/kf_glacier_3.mp4"
          ></video>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  mounted() {
    const abcde = ''
    // eslint-disable-next-line no-console
    console.log(abcde)
  }
}
</script>

<style lang="scss" scoped>
.wrap-video {
  margin-top: 7rem;
}
</style>
