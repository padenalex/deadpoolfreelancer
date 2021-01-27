<template>
  <div class="parent">

    <h1>Kinesis</h1>
    <kinesis-container :audio="audio" :playAudio="isPlaying">
      <button
          class="button"
          :class="isPlaying && 'button--playing'"
          @click="changeState"
      >hey</button>

      <kinesis-audio :audioIndex="75" type="depth" >

        <kinesis-element >
          <v-img width="100"
                 src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"/>
        </kinesis-element>

      </kinesis-audio>

    </kinesis-container>

  </div>
</template>

<script crossorigin="anonymous">
import { KinesisContainer, KinesisElement } from 'vue-kinesis'

export default {
  components: {
  },
  data() {
    return {
      audio: '/media/temp.ae912083.mp3',
      isPlaying: false
    }
  },
  methods: {
    changeState() {
      this.isPlaying = !this.isPlaying
    }
  }
}
</script>


<style>

</style>