<template>
  <div id="app">
    <Home></Home>
    <Search></Search>
    <Result></Result>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Search from './components/Search.vue'
import Result from './components/Result.vue'

export default {
  name: 'App',
  components: {
    Home,
    Search,
    Result
  }
}
</script>

<style>
html, body {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  margin-top: 10px;
  margin-bottom: 16px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
