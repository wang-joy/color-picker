<template>
  <div class="color-picker">
    <color-span class="color-span"></color-span>
  </div>
</template>

<script>
import ColorSpan from './ColorSpan'
export default {
  components: {ColorSpan}
}
</script>

<style>
  .color-picker{
    width: 400px;
    height: 300px;
    border: 1px solid #ccc;
  }
  .color-picker .color-span{
    width: 350px;
    height: 240px;
  }
</style>
