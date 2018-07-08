<template lang="pug">
  #app
    p.banner Comicomic
    router-view
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    list-style: none;
    font-family: 'Roboto';
    line-height: 1;
  }
  html, body {
    background: #f2f2f2;
  }
  #app {
    margin: 0 auto;
    width: 1024px;
  }
  .banner {
    padding: 19px 0;
    background-color: #000000;
    font-size: 36px;
    font-weight: 900;
    font-style: italic;
    color: #50FF44;
    text-align: center;
  }
</style>
