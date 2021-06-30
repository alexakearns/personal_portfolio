<template>
  <div class="site">
    <div class="site__strip">
      <!-- <Nav /> -->
    </div>
    <Home />
  </div>
</template>

<script>
// import Nav from './Nav'
import Home from './Home'

export default {
  name: 'Site',
  components: {
    // Nav,
    Home,
  }
}
</script>

<style>
/* .site {
  position:
} */
.site__strip {
  background: rgba(41, 245, 187, 1);
  position: absolute;
  left:15%;
  top: 0;

  width: 30%;
  height: 100%;
  z-index: -1;
}
</style>