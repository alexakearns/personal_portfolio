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
  border: 5px solid green;
  padding: 5px 8px;
  margin: 3px;
  border-radius: 8px;
}
</style>