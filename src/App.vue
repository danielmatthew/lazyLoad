<template>
  <div id="app"><ImageItem source="http://placehold.it/50/50" /></div>
</template>

<script>
import ImageItem from "./components/ImageItem";

export default {
  name: "App",
  components: {
    ImageItem
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
