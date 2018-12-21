<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Vote question="What is your favority Programming Language?" limit="2"/>
  </div>
</template>

<script>
import Vote from './components/Vote.vue'

export default {
  name: 'app',
  components: {
    Vote
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
