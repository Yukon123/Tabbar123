<template>
  <div id="App">
    <router-view> </router-view>
    <maintabbar></maintabbar>
  </div>
</template>

<script>
import maintabbar from "./components/maintabbar";
export default {
  name: "App",
  components: { maintabbar },
};
</script>

<style>
@import "./assets/css/basic";
</style>
