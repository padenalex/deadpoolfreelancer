<template>
  <div class="subtitle">
    <h2> Something Cool Here </h2>
  </div>
</template>

<script lang="ts">
export default {
  name: "subtitle"
}
</script>

<style scoped>
.subtitle {
  background-color: #2a2a2a;
  width: 75%;
  height: 5%;
  margin: auto;
  justify-content: center;
  display: flex;
  align-items: center;
}
.subtitle h2 {
  color: white;
  font-weight: lighter;
}
</style>