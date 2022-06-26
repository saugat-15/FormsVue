<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <InitForm />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import InitForm from './components/InitForm.vue'

export default {
  name: 'App',
  components: {
    InitForm
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
