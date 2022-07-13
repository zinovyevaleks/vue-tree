<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <TreeView/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import TreeView from "./components/TreeView.vue";

export default {
  name: "App",
  components: {
    TreeView
},
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
