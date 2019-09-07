<template>
  <div class="screen">
    <h1>Tell</h1>
  </div>
</template>

<script>
export default {
  name: 'AboutComp'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.screen{
   background-color: #21D4FD;
    background-image: linear-gradient(19deg, #21D4FD 0%, #B721FF 100%);

    border-bottom: 1px solid black;
    position: absolute;
    top: 100%;
    height: 100%;
    left: 0%;
    width: 100%;
}


</style>
