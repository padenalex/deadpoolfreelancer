<template>

  <div class="res-footer">
    <h3>Project Samples</h3>
    <div class="footer-icons">
      <ResIcon filename="icon.png" title="something"/>
      <ResIcon filename="icon.png" title="other thing"/>
      <ResIcon filename="icon.png" title="big bong"/>
      <ResIcon filename="icon.png" title="danmkk weed"/>
      <ResIcon filename="icon.png" title="memes"/>
    </div>
  </div>

</template>

<script lang="ts">
import ResIcon from "@/components/ResIcon.vue";

export default {
  name: "ResumeFooter",
  components: {
    ResIcon
  }
};

</script>

<style scoped>
.footer-icons{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin:auto;

}
.res-footer{
  bottom: 0px;
  position: absolute;
  width: 100%;
  margin: auto;
}
</style>