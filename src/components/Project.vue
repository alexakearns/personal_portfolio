<template>
  <div class="project">
    <p>Project</p>
    <h3>{{data}}</h3>
    <h1>you what</h1>
  </div>
</template>

<script>

export default {
  name: 'Project',
  props: {
    data: Object,

  }
}
</script>

<style>
.project {
  border: 5px solid fuchsia;
  padding: 0 20px;
}
</style>