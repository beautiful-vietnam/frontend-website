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
    <!-- Load Facebook SDK for JavaScript -->
    <div id="fb-root"></div>
    <script>
      window.fbAsyncInit = function() {
        FB.init({
          xfbml: true,
          version: 'v3.2'
        })
      }
      ;(function(d, s, id) {
        var js,
          fjs = d.getElementsByTagName(s)[0]
        if (d.getElementById(id)) return
        js = d.createElement(s)
        js.id = id
        js.src = 'https://connect.facebook.net/vi_VN/sdk/xfbml.customerchat.js'
        fjs.parentNode.insertBefore(js, fjs)
      })(document, 'script', 'facebook-jssdk')
    </script>

    <!-- Your customer chat code -->
    <div
      class="fb-customerchat"
      attribution="setup_tool"
      page_id="425267804880867"
      theme_color="#a41c66"
      logged_in_greeting="Chào bạn!!! Chúng tôi có thể giúp gì cho bạn?"
      logged_out_greeting="Chào bạn!!! Chúng tôi có thể giúp gì cho bạn?"
    ></div>
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
