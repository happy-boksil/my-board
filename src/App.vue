<template>
  <div id="app">
    <my-board-header></my-board-header>
    <my-board-body></my-board-body>
  </div>
</template>

<script>
import MyBoardHeader from './components/MyBoardHeader.vue'
import MyBoardBody from './components/MyBoardBody.vue'

export default {
  name: 'App',
  components: {
    MyBoardHeader,
    MyBoardBody
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
