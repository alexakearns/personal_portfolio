<template>
  <div class="project">
    <p>Project</p>
    <h2>{{ projectInfo.title }}</h2>
    <h3>{{ projectInfo.description }}</h3>
    <img :src="projectInfo.image" />
    <h4>{{ projectInfo.image }}</h4>
  </div>
</template>

<script>

export default {
  name: 'Project',
  props: {
    projectInfo: Object,
  },
  // data() {
  //   return {
  //     projectInfo
  //   }
  // } 

}
</script>

<style>
.project {
  border: 5px solid fuchsia;
  padding: 0 20px;
}
</style>