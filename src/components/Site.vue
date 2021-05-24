<template>
  <div>
    <div>
      <Nav />
    </div>
    <Home />
  </div>
</template>

<script>
import Nav from './Nav'
import Home from './Home'

export default {
  name: 'Site',
  components: {
    Nav,
    Home,
  }
}
</script>

<style>

</style>