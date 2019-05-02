<template>
  <div id="app">
    <nav class="nav justify-content-center">
      <router-link to="/">Home</router-link> &nbsp;
      <router-link to="/about">About</router-link> &nbsp;
      <router-link to="/test">Testing</router-link>
    </nav>
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
  position: fixed;
  margin-left: 0;
  width: 30%;
}
</style>
