<template>
  <div id="app">
    <Navbar></Navbar>
    <Breadcrumb></Breadcrumb>
    <Galley></Galley><Slider></Slider> <Footer></Footer><Copyright></Copyright>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Navbar from "./components/Navbar.vue";
import Breadcrumb from "./components/Breadcrumb.vue";
import Galley from "./components/Galley.vue";
import Slider from "./components/Slider.vue";
import Footer from "./components/Footer.vue";
import Copyright from "./components/Copyright.vue";

export default {
  name: "App",
  components: {
    // HelloWorld
    Navbar,
    Breadcrumb,
    Galley,
    Slider,
    Footer,
    Copyright,
  },
};
</script>

<style></style>
