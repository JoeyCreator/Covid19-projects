<template>
  <div id="app">
    <Navbar/>
    <!-- 
      The <RouterView /> component helps us display the
      current page depending on wethe route/page that
      we are on. 
    -->
    <RouterView/>
  </div>
</template>

<script>
/**
 * Here we import the navbar and register it as a component.
 */
export default {
  name: "App"
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>