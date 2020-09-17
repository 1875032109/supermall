<template>
  <div id="app">
    <main-swiper></main-swiper>
    <router-view/>
  </div>
</template>

<script>
  import mainswiper from "components/mainswiper";
  export default {
    name: 'App',
    components: {
      mainswiper
    }
  }
</script>

<style>
  @import "assets/css/base.css";
</style>

