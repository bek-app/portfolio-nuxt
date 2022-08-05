<template>
  <div>
    <div class="container-fluid">
      <MyNavbar></MyNavbar>
      <AboutMe></AboutMe>
    </div>
    <RecentPosts></RecentPosts>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'IndexPage',
})
</script>

<style lang="scss">
body {
  font-family: 'Heebo';
  color: #21243d;
}
.container-fluid {
  max-width: 1140px;
  width: 100%;
}
</style>
