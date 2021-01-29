<template>
  <q-page class="flex flex-center">
    <div class="main shadow-box" :class="'shadow-13'">
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
        <Contacts/>
        <Education/>
        <Triplebyte/>
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
import Contacts from "@/components/right/Contacts";
import Education from "@/components/right/Education";
import Triplebyte from "@/components/right/Triplebyte";

export default {
  name: 'Resume',
  components: {
    Triplebyte,
    Education,
    Contacts,
    Timeline,
    SkillStep,
    Projects,
    Heading,
    Logo,
  },
}
</script>


<style>
.main {
  margin-left:15%;
  margin-right:15%;
  margin-top:6%;
  margin-bottom:6%;
  display: inline-flex;
  flex-direction: row;
  flex-wrap: nowrap;
  width: 100%;
  max-height: fit-content;
}
.left {
  background-color: #ffffff;
  width: 70%;
  height: inherit;
}

.right {
  background-color: #062b2b;
  width: 30%;
  height: inherit;
  color: whitesmoke;
}

</style>