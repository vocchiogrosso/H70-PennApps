<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  background-color:#05546B;
  box-sizing: border-box; 
  padding: 2%;
  margin: 0;
  position: absolute;
  top: 0%;
  left: 0%;
  width: 100%;
  height: 10%;
}

#nav a {
  font-weight: bold;
  color: gray;
}

#nav a.router-link-exact-active {
  color: white;
}
</style>
