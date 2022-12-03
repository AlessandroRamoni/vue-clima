<template>
  <div id="app">
    <headerComponent />
    <homeComponent />
  </div>
</template>

<script>
import headerComponent from './components/headerComponent.vue';
import homeComponent from './components/homeComponent.vue';

export default {
  name: 'App',
  components: {
    headerComponent,
    homeComponent
  }
}
</script>

<style lang="scss">
@import "./assets/style/generics.scss";

#app {
  background-color: #e7ecec;
  text-align: center;

}
</style>
