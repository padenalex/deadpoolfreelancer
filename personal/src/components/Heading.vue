<template>
  <div class="heading">
    <h1>Alex Paden</h1>
    <div class="subtitle">
      <h4>Something Progeammr</h4>
    </div>
  </div>
</template>

<script>
export default {
name: "Heading"
}
</script>

<style scoped>
.heading{
  background-color: #00c853;
  text-align: center;
  height: fit-content;
}
.subtitle {
  background-color: #5e35b1;
  margin: 10%;
  margin-top: 0%;
  margin-bottom: 0;
}
h4 {
  margin-block-start: 0;

  display: block;
}
h1 {
  margin-block-start: 0;
  margin-block-end: 0;
  font-weight: 900;
}
</style>