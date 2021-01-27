<template>
  <div class="skillz">
  <v-row justify="center">
    <v-expansion-panels inset>

      <v-expansion-panel>
        <v-expansion-panel-header>
          header (title content)
        </v-expansion-panel-header>
        <v-expansion-panel-content>
          content here
        </v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header>
          header cageine
        </v-expansion-panel-header>
        <v-expansion-panel-content>
          <v-btn x-large>test</v-btn>
        </v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header>
          test
        </v-expansion-panel-header>
        <v-expansion-panel-content>
          kast one
        </v-expansion-panel-content>
      </v-expansion-panel>

    </v-expansion-panels>
  </v-row>
  </div>
</template>

<script>
export default {
  name: "SkillPanel",
}
</script>

<style scoped>

</style>