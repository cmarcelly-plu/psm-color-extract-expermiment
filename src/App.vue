<template>
  <div id="app">
    <AlbumsMenu/>
  </div>
</template>

<script>
import AlbumsMenu from "./components/AlbumsMenu";

export default {
  name: "App",
  components: {
    AlbumsMenu
  }
};
</script>

<style>
* {
  box-sizing: border-box;
}
html {
  height: 100%;
  overflow: auto;
}
body {
  position: relative;
  background: white;
  margin: 0;
  height: 100%;
  overflow: auto;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}
</style>
