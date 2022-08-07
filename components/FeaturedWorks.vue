<template>
  <div class="works">
    <b-row class="works__block">
      <b-col md="3"
        ><img :src="require(`../assets/images/${work.imgSrc}`)"
      /></b-col>
      <b-col>
        <h1 class="works__block-title">{{ work.title }}</h1>
        <span class="works__block-year"> {{ work.year }} </span
        ><span class="works__block-subtitle"> {{ work.subtitle }} </span>
        <p>{{ work.description }}</p>
      </b-col>
    </b-row>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'FeaturedWorks',
  props: {
    work: {
      type: Object,
      required: true,
    },
  },
})
</script>

<style lang="scss" scoped>
.works {
  border-bottom: 1px solid #e0e0e0;
  margin-top: 22px;
  padding-bottom: 15px;
  &__block {
    margin-top: 22px;

    h1 {
      font-weight: 700;
      font-size: 30px;
      line-height: 44px;
    }
    &-year {
      background: #142850;
      border-radius: 16px;
      font-weight: 900;
      font-size: 18px;
      line-height: 60px;
      color: #ffffff;
      padding: 2px;
      padding-left: 13px;
      padding-right: 8px;
      margin: 5px 38px 30px 5px;
    }
    &-subtitle {
      font-weight: 400;
      font-size: 20px;
      line-height: 29px;
      color: #8695a4;
    }
    p {
      font-weight: 400;
      font-size: 16px;
      line-height: 24px;
    }
  }
}
</style>
