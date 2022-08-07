<template>
  <div>
    <div class="container-fluid">
      <MyNavbar></MyNavbar>
      <AboutMe></AboutMe>
    </div>
    <RecentPosts></RecentPosts>
    <div class="container-fluid">
      <div class="featured__works">
        <h1 class="featured__works-title">Featured works</h1>

        <FeaturedWorks
          v-for="work in works"
          :key="work.id"
          :work="work"
        ></FeaturedWorks>
      </div>

      <MyFooter></MyFooter>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'HomePage',

  data() {
    return {
      works: [
        {
          id: 0,
          title: 'Designing Dashboards',
          imgSrc: '1.png',
          year: 2021,
          description:
            'Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.',
          subtitle: 'Dashboard',
        },
        {
          id: 1,
          title: 'Vibrant Portraits of 2020',
          imgSrc: '2.png',
          year: 2022,
          description:
            'Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.',
          subtitle: 'Illustration',
        },
        {
          id: 2,
          title: '36 Days of Malayalam type',
          imgSrc: '3.png',
          year: 2020,
          description:
            'Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.',
          subtitle: 'Typography',
        },
      ],
    }
  },
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

.featured__works {
  &-title {
    font-weight: 400;
    font-size: 22px;
    line-height: 60px;
  }
}
</style>
