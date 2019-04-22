<template>
  <section class="wrap-video container">
    <span id="play"></span>
    <img src="/img/video.png" class="image" />
    <video
      src="/video/vietnam.mp4"
      preload="auto"
      loop="true"
      class="video hidden"
    ></video>
  </section>
</template>

<script>
export default {
  mounted() {
    const video = document.getElementsByClassName('video')[0]
    const play = document.getElementById('play')
    // set current time
    video.currentTime = 50
    play.addEventListener('click', () => {
      video.classList.remove('hidden')
      play.classList.add('hidden')
      video.play()
    })
    video.addEventListener('click', () => {
      video.classList.add('hidden')
      play.classList.remove('hidden')
      video.pause()
    })
  }
}
</script>

<style lang="scss" scoped>
$color-primary: #a41c66;

.wrap-video {
  margin-top: 7rem;
  position: relative;
  .image {
    width: 100%;
    height: 607px;
  }
  .video {
    width: 100%;
    height: 625px;
    margin-top: -607px;
    animation: bounceIn 2s;
  }
}
#play {
  &:after {
    animation: bounceIn 1s;
    cursor: pointer;
    pointer-events: auto;
    content: '▶';
    height: 5rem;
    width: 5rem;
    text-align: center;
    left: 46.5%;
    top: 40%;
    position: absolute;
    z-index: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 2.5rem;
    border-radius: 45px;
    background-color: rgba(255, 255, 255, 0.637);
    color: $color-primary;
    text-shadow: 0 0.25rem 1rem rgba(black, 0.1);
    padding-left: 6px;
  }
}
.hidden {
  display: none;
  visibility: hidden;
}
@keyframes bounceIn {
  0% {
    transform: scale(0.1);
    opacity: 0;
  }
  60% {
    transform: scale(1.2);
    opacity: 1;
  }
  100% {
    transform: scale(1);
  }
}
</style>
