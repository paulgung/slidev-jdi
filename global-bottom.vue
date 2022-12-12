<template>
  <footer
      v-if="$slidev.nav.currentPage in [0,1,2,3]"
      class="absolute top-5 right-5 p-2 "
  >
    <img src="/img.png" alt="header" width="160">
  </footer>
</template>

<script>
export default {
  name: "global-bottom.vue"
}
</script>

<style scoped>

</style>