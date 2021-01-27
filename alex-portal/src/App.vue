<template>
  <v-app style="background: #e5c5a7;">
    <v-app-bar app color="primary" dark absolute>
      <div class="d-flex align-center">
        <v-img class="shrink mr-2" contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition" width="40"/>
        <v-img
          class="shrink mt-1 hidden-sm-and-down" contain min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"/>
      </div>
    </v-app-bar>




    <v-main>
      <v-container fluid>
        <router-view></router-view>
      </v-container>
    </v-main>




    <v-footer app padless style="background-color: #b4f837" absolute>
      <v-col
          class="text-center"
          cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Cool Guy Inc</strong>
      </v-col>
    </v-footer>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import Home from "./views/Home.vue";

export default Vue.extend({
  name: "App",
});
</script>
