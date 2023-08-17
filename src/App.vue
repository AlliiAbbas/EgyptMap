<template>
  <egypt-map/>
</template>

<script>
import EgyptMap from './components/EgyptMap.vue'

export default {
  name: 'App',
  components: {
    EgyptMap
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
