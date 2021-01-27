<template>
  <div class="icon">
    <img :src="require(`@/assets/${filename}`)">
    <h5>{{title}}</h5>
  </div>
</template>

<script lang="ts">
export default {
  name: "ResIcon",
  props: {
    title: String,
    filename: String
  }
}
</script>

<style scoped>
.icon {
  margin: auto;
}
h5 {
  margin-top: 0;
}
</style>