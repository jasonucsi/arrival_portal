<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/ucsi_logo_footer.png">
    <LandingComponent/>
  </div>
</template>

<script>
import LandingComponent from './components/Landing.vue'

export default {
  name: 'App',
  components: {
    LandingComponent
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
