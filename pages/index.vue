<template>
  <div>
    <my-header />
    <guide />
    <instagram />
  </div>
</template>

<script>
import MyHeader from '~/components/header'
import Guide from '~/components/guide'
import Instagram from '~/components/instagram'

export default {
  components: {
    MyHeader,
    Guide,
    Instagram
  }
}
</script>
