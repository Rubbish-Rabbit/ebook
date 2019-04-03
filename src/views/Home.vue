<template>
  <div class="home">
    <span class="icon-bookmark"></span>
    <span class="icon-clock"></span>
  </div>
</template>

<script>
  import Epub from 'epubjs'
  global.ePub = Epub
  export default {
  }
</script>

<style scoped>
  .icon-bookmark{
    font-size:80px;
    color: red;
  }
</style>
