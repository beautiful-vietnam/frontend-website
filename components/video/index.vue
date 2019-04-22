<template>
  <section class="wrap-video container">
    <img
      src="/img/cover.png"
      class="image"
    />
    <video
      src="https://www.youtube.com/watch?v=OWxS6EOOVkg"
      preload="auto"
      loop="true"
      class="video"
    ></video>
  </section>
</template>

<script>
export default {
  mounted() {
    const video1 = document.getElementsByClassName('video')[0]
    video1.play()
  }
}
</script>

<style lang="scss" scoped>
.wrap-video {
  margin-top: 7rem;
  position: relative;
  .image {
    width: 100%;
    height: 600px;
    position: absolute;
  }
  .video-first {
    width: 100%;
    height: 600px;
    position: absolute;
  }
}
</style>
