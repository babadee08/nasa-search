<template>
  <div id="app">
    <img src="./assets/logo.png">
    <search></search>
  </div>
</template>

<script>
import Hello from './components/Hello'
import Search from "./components/Search";

export default {
  name: 'app',
  components: {
      Search,
      Hello
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
