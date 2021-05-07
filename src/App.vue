<template>
  <div id="app">
      <add-header></add-header>
    <img class="logo" alt="Vue logo" src="./assets/logo.png">
    <Index msg="Welcome to ToDo App"/>
    <add-footer></add-footer>
  </div>
</template>

<script>
import Index from './components/Index.vue'
import header from "./components/Header.vue";
import footer from "./components/Footer.vue";
export default {
  name: 'App',
  components: {
    Index,
    'add-header': header,
    'add-footer': footer
  }
}
</script>

<style>
body {
    margin:0px;
    padding:0px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.logo {
    height:130px
}

</style>
