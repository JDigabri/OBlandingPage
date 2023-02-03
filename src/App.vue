<template>
  <div class="navCont">
  <nav>
    <router-link to="/"></router-link>
  </nav>
</div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.navCont{
  position: fixed;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100vw;
  height: 50px;
  background-color: #FFC563;
  /*background-color: #6198FF;*/
  z-index: 4;
  font-size: 28px;

}

nav a {
  font-weight: bold;
  color: #FFFFFF;
}

nav a.router-link-exact-active {
  color: #FFFFFF;
  text-decoration: none;
}

body{
  margin: 0;
  overflow-x: hidden;
}
</style>
