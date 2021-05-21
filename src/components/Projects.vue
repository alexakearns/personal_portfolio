<template>
  <div class="projects">
    <Project />
    <Project />
    <Project />
    <Project />
  </div>
</template>

<script>
import Project from './Project';

export default {
  name: 'Projects',
  components: {
    Project
  }
}
</script>

<style>
.projects {
  border: 5px solid purple;
  display: flex;
  justify-content: space-evenly;
}
</style>