<template>
    <div class="projects">
      <q-tabs no-caps active-color="primary" indicator-color="transparent" class="text-grey" v-model="tab">
        <q-tab name="images" label="Images" icon="settings" style="width: 150px; height: 150px;"></q-tab>
        <q-tab name="videos" label="Videos" icon="settings" style="width: 150px; height: 150px;"></q-tab>
        <q-tab name="articles" label="Articles" icon="settings" style="width: 150px; height: 150px;"></q-tab>
      </q-tabs>
    </div>
</template>

<script>
export default {
name: "Projects"
}
</script>

<style scoped>

</style>