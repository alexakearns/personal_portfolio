<template>
  <div class="projects">
    <div v-for="project in projectsData" v-bind:key="project.title">
      
    <Project :projectInfo="project"/>
    </div>
    
    <!-- <Project /> -->
  </div>
</template>

<script>
import Project from './Project';
// import axios from 'axios'
import json from '../content/ProjectDetails.json'

export default {
  name: 'Projects',
  components: {
    Project
  },
  data() {
    return {
      projectsData: json,
    }
  },
  mounted() {
    console.log(this.data)
    console.log('first obj ', this.data.missionCtrl.tools

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