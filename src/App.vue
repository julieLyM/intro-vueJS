<template>
  <div id="app">
    <HelloWorld
      msg="Licorne world"
      href="https://unicorn.mrtino.eu/"
      licorneUrl="https://unicorn.mrtino.eu/#100,0,0,100,0,0,0,100,0,0,100,0,1,0,0"
      text="test props licorne"
      question="false"
    />
    <Stackerine />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Stackerine from "./components/Stackerine.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Stackerine
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
