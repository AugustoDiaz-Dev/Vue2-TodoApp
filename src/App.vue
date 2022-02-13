<template>
  <div id="app">
    <Header />
    <router-view />
  </div>
</template>

<script>
import Header from "./components/layout/Header.vue";
export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
  max-width: 960px;
  margin: 0 auto;
  margin-top: 8rem;
  background-color: #333;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  border: 4px solid #42b983;
}
#nav a {
  font-weight: bold;
  color: #fff;
}
#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
