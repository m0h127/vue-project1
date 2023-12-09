<template>
  <FirstComponentVue></FirstComponentVue>
  <img alt="Vue logo" src="./assets/logo.png">
  <SecondComponentVue></SecondComponentVue>

</template>

<script>
import FirstComponentVue from './components/FirstComponent.vue'
import SecondComponentVue from './components/SecondComponent.vue'

export default {
  name: 'App',
  components: {
    FirstComponentVue,
    SecondComponentVue
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