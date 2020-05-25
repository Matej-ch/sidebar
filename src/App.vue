<template>
  <div id="app">
    <side-navbar/>
  </div>
</template>

<script>
import SideNavbar from './components/SideNavbar.vue'

export default {
  name: 'App',
  components: {
    SideNavbar
  }
}
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
