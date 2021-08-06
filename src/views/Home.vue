<template>
  <div class="h-auto flex flex-col justify-center items-center">
    <NamePic/>
    <Spotify/>
  </div>
</template>

<script>
import NamePic from '../components/NamePic.vue'
import Spotify from '../components/Spotify.vue'

export default {
  components: {
    NamePic,
    Spotify
  }
}
</script>
