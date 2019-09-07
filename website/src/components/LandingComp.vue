<template>
  <div class="screen">
    <img src="../assets/Logo.png"/>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
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
    background-color: white;
    border-bottom: 1px solid black;
    position: absolute;
    top: 15%;
    height: 85%;
    left: 0%;
    width: 100%;
}


</style>
