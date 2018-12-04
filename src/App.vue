<template>
  <div id="app">
    <color-picker></color-picker>
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
  }
}
</script>

<style>
</style>
