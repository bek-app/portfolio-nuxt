<template>
  <div class="recent__posts">
    <div class="container-fluid">
      <b-row>
        <b-col><h2 class="recent__posts-title">Recent posts</h2></b-col>
        <b-col md="4" class="ml-auto" align-self="center"
          ><p class="text-right recent__posts-text">View all</p></b-col
        >
      </b-row>
      <b-row>
        <b-col>
          <div class="recent__posts-block">
            <h2>
              Making a design system from <br />
              scratch
            </h2>
            <span>12 Feb 2020</span> | <span>Design, Pattern</span>
            <p>
              Amet minim mollit non deserunt ullamco est sit <br />
              aliqua dolor do amet sint. Velit officia consequat <br />
              duis enim velit mollit. Exercitation veniam <br />
              consequat sunt nostrud amet.
            </p>
          </div>
        </b-col>
        <b-col>
          <div class="recent__posts-block">
            <h2>
              Creating pixel perfect icons in <br />
              Figma
            </h2>
            <span>12 Feb 2020</span> | <span>Figma, Icon Design</span>
            <p>
              Amet minim mollit non deserunt ullamco est sit <br />
              aliqua dolor do amet sint. Velit officia consequat <br />
              duis enim velit mollit. Exercitation veniam <br />
              consequat sunt nostrud amet.
            </p>
          </div></b-col
        ></b-row
      >
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'RecentPosts',
})
</script>

<style lang="scss" scoped>
.recent__posts {
  background: #edf7fa;
  height: 396px;
  font-weight: 400;
  &-title {
    font-weight: 400;
    font-size: 22px;
    line-height: 60px;
  }
  &-text {
    font-size: 16px;
    line-height: 24px;
    text-align: right;
    color: #00a8cc;
  }
  &-block {
    background: #ffffff;
    box-shadow: 0px 4px 10px rgba(187, 225, 250, 0.25);
    border-radius: 4px;
    padding: 21px;
    h2 {
      font-weight: 700;
      font-size: 26px;
      line-height: 38px;
    }
    span {
      font-size: 18px;
      line-height: 26px;
      margin: 17px 0;
    }
    p {
      font-size: 16px;
      line-height: 24px;
    }
  }
}
</style>
