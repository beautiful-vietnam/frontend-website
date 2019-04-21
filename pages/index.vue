<template>
  <div>
    <my-header />
    <guide />
    <instagram />
    <introduction />
    <my-video />
  </div>
</template>

<script>
import MyHeader from '~/components/header'
import Guide from '~/components/guide'
import Instagram from '~/components/instagram'
import Introduction from '~/components/introduction'
import MyVideo from '~/components/video'

export default {
  components: {
    MyHeader,
    Guide,
    Instagram,
    Introduction,
    MyVideo
  }
}
</script>
