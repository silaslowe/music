<template>
  <div
  class="h-screen bg-red-200">
    <Nav/>
  </div>
</template>

<script>
import {Nav} from './Nav.vue'

export default {
  name: "Container",
  components: {
    Nav
  }
}
</script>

<style scoped>

</style>