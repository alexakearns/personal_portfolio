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
  /* border: 5px solid; */
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  margin: 100px ;
  /* background: rgba(41, 245, 187, 1); */
  background: #150E58;
  padding: 20px;
  min-height: 500px;
}

.home__name {
  color: #fff;
  font-size: 70px;
  font-weight: 9000;
  font-family: 'Just Me Down Here Again', cursive;
}

.home__content {
  display: flex;
}

</style>