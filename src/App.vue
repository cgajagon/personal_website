<template>
  <HelloWorld/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
body {
  background-image: url('./assets/flying_landscape_v2.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  position: relative;
  min-height: 840px;
}

#app {
  font-family: 'Trebuchet MS', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
