<template>
  <div class="container mx-auto">
    <home-hero />
    <home-hero />
    <home-hero />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { smallCardSections, largeCardSections } from '@/assets/data.js'
import '@/styles/global.scss'

export default Vue.extend({
  name: 'IndexPage',
  data() {
    return {
      largeCardInfo: largeCardSections,
      smallCardInfo: smallCardSections,
    }
  },
})
</script>

<style lang="scss">
@import '@/styles/fonts.scss';

body {
  font-family: 'SF Mono';
}
</style>
