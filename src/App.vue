<template>

  <Site info="hello there"/>
</template>

<script>
import Site from './components/Site.vue'

export default {
  name: 'App',
  components: {
    Site
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
}
</style>
