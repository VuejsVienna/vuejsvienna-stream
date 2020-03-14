<template>
  <div id="app">
    <img alt="vienna.go (Golang) logo" src="./assets/logo.png" class="logo-image">
    <StreamInfo />
  </div>
</template>

<script>
import StreamInfo from './components/StreamInfo'

export default {
  name: 'App',
  components: {
    StreamInfo
  }
}
</script>

<style>
body {
  background: #0e0e0e;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 60px;
}
.logo-image {
  height: 250px;
}
</style>
