<template>
  <div id="app">
    <sleep />
  </div>
</template>

<script>
import Sleep from './components/Sleep.vue'

export default {
  name: 'app',
  components: {
    Sleep
  }
}
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
