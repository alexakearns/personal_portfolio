<template>
  <div class="home">
      <Nav />
    <h1 class="home__name">Alexa Kearns</h1>
    <div class="home__content">
      <About />
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
  background: #150E58;
  border-radius: 8px;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  left: 10%;
  min-height: 500px;
  padding: 20px;
  position: absolute;
  right: 10%;
  top: 15%;
}

.home__name {
  color: #fff;
  font-size: 70px;
  font-family: 'Just Me Down Here Again', cursive;
  font-weight: 9000;
}

.home__content {
  display: flex;
}

</style>