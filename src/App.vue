<template>
  <div id="app">
    <NavUp />
    <Content />
    <content-down />
    <Footer />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import NavUp from "./components/NavUp.vue";
import Content from "./components/Content.vue";
import Footer from "./components/Footer.vue";
import ContentDown from "./components/ContentDown.vue";

export default {
  name: "App",
  components: {
    NavUp,
    Content,
    ContentDown,
    Footer
  }
};
</script>

<style>
#app {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji",
    "Segoe UI Symbol";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
