<template>
  <div class="app">
    <home-header></home-header>
  </div>
</template>

<script>
import HomeHeader from '@/components/HomeHeader'
export default {
  name: 'App',
  components: {
    HomeHeader
  }
}
</script>

<style lang="scss">
@import '@/assets/scss/main.scss';
</style>
