<template>
  <div id="app" :style="{backgroundColor: val}">
    <color-picker v-model="val" :color-format='colorFormat'></color-picker>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import ColorPicker from './components/color-picker/ColorPicker'
export default {
  name: 'App',
  components: {
    HelloWorld,
    ColorPicker
  },
  data () {
    return {
      val: '#cccccc',
      colorFormat: 'hex'
    }
  }
}
</script>

<style>
</style>
