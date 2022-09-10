<template>
  <Indesicion/>
</template>

<script>
import Indesicion from "./components/Indesicion.vue";

export default {
  name: 'App',
  components: {
    Indesicion
  }
}
</script>

<style>
html, body {
  background-color: black;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
