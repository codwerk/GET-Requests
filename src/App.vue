<template>
  <div id="app">
    <show-blogs></show-blogs>
  </div>
</template>

<script>

import showBlogs from './components/showBlogs'

export default {
  name: 'App',
  components: {
    'show-blogs': showBlogs
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
