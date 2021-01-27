<template>
  <v-container>
    <v-timeline dense>
      <v-timeline-item
        v-for="(item, i) in positions"
        :key="i"
        :title="item.title"
        :subtitle="item.subtitle"
        :description="item.description"
        small>

        <h3>{{item.title}}</h3>
        <h4>{{item.subtitle}}</h4>
        <v-text>{{item.description}}</v-text>

      </v-timeline-item>
    </v-timeline>
  </v-container>
</template>

<script lang="ts">
export default {
  name: "WorkHistory",

  data: () => ({
    positions: [
      {
        i: 1,
        title: 'fucking ganbgster',
        subtitle: 'kill ppl inc.',
        description:'is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.'
      },
      {
        i: 2,
        title: 'big man',
        subtitle: '1969',
        description:'t is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using \'Content here, content here\', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for \'lorem.'
      },
      {
        i: 3,
        title: 'small man',
        subtitle: 'short person and company',
        description:'The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.'
      }
    ],
  }),
}
</script>

<style scoped>
h3 {
  font-size: medium;
}
h4 {
  font-size: smaller;
  font-weight: lighter;
  font-style: italic;
}

v-text {
  font-size: x-small;
}
v-container {
  margin: auto;
}
</style>