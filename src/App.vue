<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Header></Header>
    <Jumbotron></Jumbotron>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
import Jumbotron from "./components/Jumbotron.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    Header,
    Main,
    Footer,
    Jumbotron,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss"
</style>
