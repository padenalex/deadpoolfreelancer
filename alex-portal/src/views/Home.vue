<template>
  <div class="home">
    <Resume/>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Resume from "@/components/Resume.vue";

export default Vue.extend({
  name: "Home",
  components: {
    Resume
  }
});
</script>
