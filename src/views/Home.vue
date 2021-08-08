<template>
  <div class="h-auto flex flex-col justify-center items-center">
    <NamePic/>
    <Spotify/>
    <Footer/>
  </div>
</template>

<script>
import NamePic from '../components/NamePic.vue'
import Spotify from '../components/Spotify.vue'
import Footer from '../components/Footer.vue'

export default {
  components: {
    NamePic,
    Spotify,
    Footer
  }
}
</script>
