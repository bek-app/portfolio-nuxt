<template>
  <div class="about">
    <b-row align-h="between">
      <b-col>
        <h1 class="about-title">
          Hi, I am John, <br />
          Creative Technologist
        </h1>
        <p class="about-text">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
          <br />
          sint. Velit officia consequat duis enim velit mollit. Exercitation
          veniam <br />
          consequat sunt nostrud amet.
        </p>
        <b-button class="about-btn"> Download Resume </b-button>
      </b-col>
      <b-col md="4" class="ml-auto">
        <img src="~/assets/images/avatar.png" alt="" />
      </b-col>
    </b-row>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'AboutMe',
})
</script>

<style lang="scss" scoped>
.about {
  margin-top: 140px;
  margin-bottom: 70px;
  &-title {
    font-weight: 700;
    font-size: 44px;
    line-height: 60px;
    color: #21243d;
  }
  &-text {
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    color: #21243d;
  }
  &-btn {
    font-weight: 500;
    font-size: 20px;
    line-height: 29px;
    background: #ff6464;
    border-radius: 2px;
    color: #ffffff;
    border: none;
  }
}
</style>
