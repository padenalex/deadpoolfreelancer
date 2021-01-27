<template>
  <v-container>
    <div class="resume">

      <div class="wrapper">
        <div class="left">
          <h1>ALEX PADEN</h1>
          <MusicBox/>
          <Subtitle/>
          <br/>
          <SkillPanel/>
          <br/>
          <hr/>

          <h2>WORK EXPERIENCE</h2>
          <WorkHistory/>
          <hr>
          <p>ggg</p>
          <ResumeFooter/>
        </div>
        <div class="right">
          Very long content
        </div>
      </div>

    </div>
  </v-container>
</template>

<script lang="ts">
import Vue from "vue";
import ResumeFooter from "@/components/ResumeFooter.vue";
import Subtitle from "@/components/Subtitle.vue";
import WorkHistory from "@/components/WorkHistory.vue";
import SkillPanel from "@/components/SkillPanel.vue"
import MusicBox from "@/components/MusicBox.vue";

export default Vue.extend({
  name: "Resume",
  components: {
    ResumeFooter,
    Subtitle,
    WorkHistory,
    SkillPanel,
    MusicBox
  },
});
</script>

<style scoped>
h1 {
  font-size: 75px;
  padding-bottom: 0%;
  margin-bottom: 0;
  text-align: center;
}

.wrapper {
  display: flex;
}

.left {
  background: white;
  height: 150vh;
  width: 70%;
  position: relative;
  padding: 3%;
}

.right {
  background: #2a2a2a;
  color: white;
  width: 30%;
  height: 150vh;
  position: relative;
}

.resume {
  position: relative;
  padding-left: 12%;
  padding-right: 12%;
}
</style>
