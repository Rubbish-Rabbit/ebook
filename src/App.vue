<template>
  <div id="app">
    <span class="text">ABCD</span>
    <router-view/>
  </div>
</template>

<script>
  export default {}
  document.addEventListener('DOMContentLoaded', () => {
    const html = document.querySelector('html')
    let fontSize = window.innerWidth / 10
    html.style.fontSize = fontSize = 'px'
  })
</script>

<style scoped>
  .text {
    font-family: "Days One", serif;
    font-size: 20px;
    color: orange;
  }
</style>
