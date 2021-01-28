<template>
  <q-page class="flex flex-center" style="background-color: #66bb6a">

    <div class="main">
      <div class="left">

        <Heading/>
        <br/>

        <SkillStep/>
        <br/>

        <Timeline/>
        <br/>

        <Projects/>

      </div>

      <div class="right">
        <Logo/>
      </div>
      <div class="flex-break q-py-md"></div>
    </div>

  </q-page>
</template>

<script>
import SkillStep from "@/components/left/SkillStep";
import Timeline from "@/components/left/Timeline";
import Projects from "@/components/left/Projects";
import Heading from "@/components/left/Heading";
import Logo from "@/components/right/Logo";

export default {
  name: 'Resume',
  components: {
    Timeline,
    SkillStep,
    Projects,
    Heading,
    Logo
  },
}
</script>


<style>
.main {
  margin-left: 10%;
  margin-right: 10%;
  display: inline-flex;
  flex-direction: row;
  flex-wrap: nowrap;
  width: 100%;
}
.left {
  background-color: #b4f837;
  width: 70%
}

.right {
  background-color: #00acc1;
  width: 30%
}

</style>