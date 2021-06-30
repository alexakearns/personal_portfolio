<template>
  <div class="nav-bar">
    <Button btn="Home"/>
    <Button btn="Projects"/>
    <Button btn="Mini Projects"/>
    <Button btn="Contact"/>
  </div>
</template>

<script>

import Button from './Button.vue'
export default {
  name: 'Nav',
  components: {
    Button
  }
}
</script>

<style>
.nav-bar {
  display: flex;
  /* flex-wrap: wrap; */
  justify-content: space-around;
  /* border: 2px solid blue; */
  width: 100%;
  margin: 10px;
}
</style>