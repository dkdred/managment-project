<template>
  <div id="app">
    <header-banner></header-banner>
    <router-view/>
    <slide>
      <a id="home" href="#">
        <span>Home</span>
      </a>
    </slide>

  </div>
</template>

<script>
  import HeaderBanner from "./components/HeaderBanner";
  import { Slide } from 'vue-burger-menu'

  export default {
    name: 'App',
    components: {
      HeaderBanner,
      Slide
    }
  }
</script>

<style>

</style>
