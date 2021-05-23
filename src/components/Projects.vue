<template>
  <div class="projects">
    <Project />
    <Project />
    <Project />
  </div>
</template>

<script>
import Project from './Project';
// import axios from 'axios'
import json from '../content/data.json'

export default {
  name: 'Projects',
  components: {
    Project
  },
  data() {
    return {
      data: json,
    }
  },
  mounted() {
    console.log(this.data)
    console.log('first obj ', this.data.missionCtrl.tools[0]
    )
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