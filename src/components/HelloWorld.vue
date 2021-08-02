<template>
  <div class="main">
    <h1 class="text">Carlos Gajardo Gonzalez</h1>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div {
  width: 100%;
  height: 100%;
  background-image: url("../assets/flying_landscape.jpg");
  background-size: cover;
  background-position: center;
}
.text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

</style>
