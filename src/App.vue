<template>
  <div id="app">
    <headerComponent />
    <homeComponent msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import headerComponent from "./components/headerComponent.vue";
import homeComponent from './components/homeComponent.vue'

export default {
  name: 'App',
  components: {
    headerComponent,
    homeComponent
  }
}
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
