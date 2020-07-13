<template>
  <div id="app">
    <ishwarcarousel/>
  </div>
</template>

<script>
import ishwarcarousel from './components/ishwarCarousel.vue'

export default {
  name: 'App',
  components: {
    ishwarcarousel
  }
}
</script>

<style>
#app {
  font-family: Helvetica,;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
