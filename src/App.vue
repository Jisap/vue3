<template>
  <div id="app">
    <p>El contador marca: N</p>
  </div>
</template>

<script>
import { ref } from "@vue/composition-api";

export default {
  name: "App",
  setup() {
    const contador = ref(0);
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
