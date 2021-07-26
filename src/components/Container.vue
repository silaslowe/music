<template>
  <div class="flex justify-center align-center">
    <div
        class="mx-4 my-6 h-screen border-8 w-4/5 border-black flex justify-center align-center">
      <div class="w-1/2 h-full flex justify-center align-center">
        <Logo/>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from "@/components/Logo";

export default {
  name: "Container",
  components: {Logo}
}
</script>

<style scoped>

</style>