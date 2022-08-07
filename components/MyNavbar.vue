<template>
  <div>
    <b-navbar toggleable="lg">
      <b-navbar-toggle target="nav-collapse" class="ml-auto"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav class="ml-auto">
        <b-navbar-nav class="ml-auto">
          <NuxtLink class="my-link" to="#">Home </NuxtLink>
          <NuxtLink class="my-link" to="#">Works</NuxtLink>
          <NuxtLink class="my-link" to="#">Contact</NuxtLink>
          <NuxtLink class="my-link" to="#">Blog</NuxtLink>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'MyNavbar',
})
</script>

<style lang="scss">
.navbar-light {
  .navbar-nav {
    .my-link {
      margin-right: 15px;
      font-family: 'Heebo';
      font-style: normal;
      font-weight: 500;
      font-size: 20px;
      line-height: 29px;
      text-align: right;
      color: #000000 !important;
    }
  }
}
</style>
