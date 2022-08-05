<template>
  <div>
    <b-navbar toggleable="lg">
      <b-navbar-toggle target="nav-collapse" class="ml-auto"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav class="ml-auto">
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Works </b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
          <b-nav-item href="#">Blog</b-nav-item>
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
    .nav-link {
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
