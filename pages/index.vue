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
import MyHeader from '~/components/header'
import Guide from '~/components/guide'
import Instagram from '~/components/instagram'
import Introduction from '~/components/introduction'
import MyVideo from '~/components/video'
import Blog from '~/components/blog'
import MyFooter from '~/components/footer'
import Slide from '~/components/slide'

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
