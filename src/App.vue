<template>
  <div id="app">
    <HelloWorld/>
    <Example/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Example from "./components/Example";

export default {
  name: "App",
  components: {
    HelloWorld,
    Example
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
