<template>
  <div class="button">
  <button flat>{{ btn }}</button>
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
  /* border: 1px solid black; */
  /* background: #FAF9F6; */
  color: #1E3151;
  padding: 5px 8px;
  margin: 3px;
  border-radius: 8px;
  width: 120px;
}
button:hover {
  color: #fff;
}
</style>