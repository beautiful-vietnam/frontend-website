<template>
  <section class="wrap-slide">
    <img
      src="/img/arrow-left.png"
      alt="arrow left"
      class="arrow-left"
      @click="previos"
    />
    <img
      v-for="(item, index) in listImage"
      :key="index"
      :class="`slide-${index + 1}`"
      :src="`/img/slide${item.id}.png`"
      :alt="`slide image ${index + 1}`"
    />
    <img
      src="/img/arrow-right.png"
      alt="arrow left"
      class="arrow-right"
      @click="next"
    />
  </section>
</template>

<script>
export default {
  data() {
    return {
      listImage: [
        {
          id: 1,
          src: '/img/slide1.png'
        },
        {
          id: 2,
          src: '/img/slide2.png'
        },
        {
          id: 3,
          src: '/img/slide3.png'
        },
        {
          id: 4,
          src: '/img/slide4.png'
        },
        {
          id: 5,
          src: '/img/slide5.png'
        }
      ]
    }
  },
  methods: {
    next() {
      const imageFirst = this.listImage[0]
      this.listImage.shift()
      this.listImage.push(imageFirst)
    },
    previos() {
      const imageLast = this.listImage[4]
      this.listImage.pop()
      this.listImage.splice(0, 0, imageLast)
    }
  }
}
</script>

<style lang="scss" scoped>
.wrap-slide {
  margin-top: 7rem;
  position: relative;
  height: 30rem;
  .slide-3 {
    z-index: 100;
    left: 50%;
    top: 50%;
    margin-left: -320px;
    margin-top: -240px;
    width: 640px;
    height: 480px;
    &:after {
      content: 'abcde';
      display: block;
      color: red;
      z-index: 110;
    }
  }
  .slide-4 {
    z-index: 90;
    left: 50%;
    top: 50%;
    margin-left: -70px;
    margin-top: -215px;
    width: 580px;
    height: 430px;
  }
  .slide-2 {
    z-index: 80;
    left: 50%;
    top: 50%;
    margin-left: -510px;
    margin-top: -215px;
    width: 580px;
    height: 430px;
  }
  .slide-1 {
    z-index: 70;
    left: 50%;
    top: 50%;
    margin-left: -635px;
    margin-top: -158px;
    width: 470px;
    height: 316px;
  }
  .slide-5 {
    z-index: 60;
    left: 50%;
    top: 50%;
    margin-left: 165px;
    margin-top: -158px;
    width: 470px;
    height: 316px;
  }
  .arrow-left {
    margin-left: -340px;
  }
  .arrow-right {
    margin-left: 300px;
  }
}
.arrow-left,
.arrow-right {
  top: 50%;
  left: 50%;
  margin-top: -20px;
  margin-left: -20px;
  z-index: 110;
  cursor: pointer;
}

.slide-1,
.slide-2,
.slide-3,
.slide-4,
.slide-5,
.arrow-left,
.arrow-right {
  position: absolute;
}
</style>
