<template>
  <div>
    <my-header />
    <guide />
    <instagram />
    <introduction />
    <blog />
    <my-video />
    <slide />
    <my-footer />
  </div>
</template>

<script>
import {
  MyHeader,
  MyFooter,
  MyVideo,
  Instagram,
  Introduction,
  Blog,
  Slide,
  Guide
} from '~/components'

export default {
  components: {
    MyHeader,
    Guide,
    Instagram,
    Introduction,
    MyVideo,
    Blog,
    MyFooter,
    Slide
  }
}
</script>
