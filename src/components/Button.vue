<template>
  <div class="button">
  <btn>{{ btn }}
  </btn>
  </div>
</template>

<script>
export default {
  name: 'Button',
  props: {
    btn: String
    }
}
</script>

<style>
.button {
  border: 1px solid black;
  background: #FAF9F6;
  padding: 5px 8px;
  margin: 3px;
  border-radius: 8px;
}
</style>