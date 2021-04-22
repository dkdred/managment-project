<template>
  <div id="app">
    <header-banner></header-banner>
    <router-view/>
    <slide>
      <a id="home" href="#">
        <span>Home</span>
      </a>
      <router-link to="/products" id="products">
        Продукты
      </router-link>
    </slide>
    <Footer></Footer>
  </div>
</template>

<script>
  import HeaderBanner from "./components/HeaderBanner";
  import { Slide } from 'vue-burger-menu'
  import Footer from "./components/Footer";

  export default {
    name: 'App',
    components: {
      HeaderBanner,
      Slide,
      Footer
    }
  }
</script>

<style>

</style>
