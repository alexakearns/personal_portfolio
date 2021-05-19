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
  flex-wrap: wrap;
  border: 5px solid blue;
  width: 200px;
}
</style>