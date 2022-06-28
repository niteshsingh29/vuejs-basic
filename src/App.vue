<template>
  <parentComponent />
</template>

<script>
import parentComponent from "./components/parentcomponent.vue";
export default {
  name: "App",
  components: {
    parentComponent,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
