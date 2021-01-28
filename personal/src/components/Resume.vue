<template>
  <q-page class="flex flex-center">

    <div class="main">
      <div class="left">
        <h1>Alex Paden</h1>

        <br/>
        <SkillStep/>
        <br/>
        <Timeline/>


        <Projects/>
      </div>
      <div class="right">
        <div id="q-app">
          <div class="q-pa-md">
            <q-card style="max-width: 300px">
              <q-item>
                <q-item-section avatar>
                  <q-skeleton type="QAvatar"></q-skeleton>
                </q-item-section>

                <q-item-section>
                  <q-item-label>
                    <q-skeleton type="text"></q-skeleton>
                  </q-item-label>
                  <q-item-label caption>
                    <q-skeleton type="text"></q-skeleton>
                  </q-item-label>
                </q-item-section>
              </q-item>

              <q-skeleton height="200px" square></q-skeleton>

              <q-card-actions align="right" class="q-gutter-md">
                <q-skeleton type="QBtn"></q-skeleton>
                <q-skeleton type="QBtn"></q-skeleton>
              </q-card-actions>
            </q-card>
          </div>
        </div>
      </div>
      <div class="flex-break q-py-md"></div>
    </div>

  </q-page>
</template>

<script>
import SkillBox from "@/components/SkillBox";
import SkillStep from "@/components/SkillStep";
import Timeline from "@/components/Timeline";
import Projects from "@/components/Projects";

export default {
  name: 'Resume',
  components: {
    Timeline,
    SkillStep,
    Projects
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