<template>
  <div id="app">
     <h1>Truck Stop App</h1>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div>
      <Map />
    </div>
     <frontpage/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Map from "./components/Map";
import frontpage from "./components/frontPage.vue";
export default {
  name: "app",
  components: {
    frontpage,
    HelloWorld,
    Map,
  },
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
