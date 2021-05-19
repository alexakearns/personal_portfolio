<template>
  <div class="home">
    <h1>Alexa Kearns</h1>
    <h4>{{info}}</h4>
    <div class="content">
      <Nav />
      <About />
    </div>
  </div>
</template>

<script>

import Nav from './Nav';
import About from './About';

export default {
  name: 'Home',
  props: {
    info: String
  },
  components: {
    Nav,
    About
  }
}
</script>

<style>
.home {
  border: 5px solid;
}
.content {
  display: flex;
}

</style>