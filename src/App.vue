<template>
  <div>
    <Header />
    <Body />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Body from "./components/Body.vue";

export default {
  components: { Header, Body },
  data() {
    return {};
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
