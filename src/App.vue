<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Header></Header>
    <Footer></Footer>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
// import Main from './components/Main.vue';
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    Header,
    // Main,
    Footer,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss"
</style>
