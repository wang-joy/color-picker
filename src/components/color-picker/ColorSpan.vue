<template>
  <div class="color-span">
    <div class="color-span-white"></div>
    <div class="color-span-black"></div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  .color-span{
    position: relative;
  }
  .color-span .color-span-white, .color-span .color-span-black{
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
  }
  .color-span .color-span-white{
    background: linear-gradient(90deg,#fff,hsla(0,0%,100%,0));
  }
  .color-span .color-span-black{
    background: linear-gradient(0deg,#000,transparent);
  }
</style>
