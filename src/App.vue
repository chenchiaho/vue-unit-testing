<template>
  <NavBar />
  <img alt="Vue logo" src="./assets/logo.png">
  <ToDoApp/>
</template>

<script>
import ToDoApp from './components/ToDoApp.vue'
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    ToDoApp,
    NavBar
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
