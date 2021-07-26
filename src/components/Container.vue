<template>
  <div style="display: flex; justify-content: center; align-items: center;">
    <div
        style="margin: 1rem; border: 8px solid black; width:80%; display:
        flex; align-items: center; justify-content: center;">
<!--      <div style="display: flex; justify-content: center; align-items: center;">-->
        <Logo/>
<!--      </div>-->
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