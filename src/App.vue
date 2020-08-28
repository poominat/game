<template>
  <div id="app">
    <br />
    <img class="rounded-circle" src="https://i.pinimg.com/originals/e0/4a/1b/e04a1b6e6b273caa416f0ced917ac494.jpg" width="20%" />
    <HelloWorld msg = "Battle Fighters" />
    <br />
    
    <div>
      <botton />
    </div>
  </div>
</template>
<script>
import HelloWorld from "./components/HelloWorld.vue";
import botton from "./components/botton.vue";
export default {
  name: "App",
  components: {
    HelloWorld,
    botton,
  },
};
</script>

<style>
#app {
  background-image: url(https://data.photofunky.net/output/image/d/c/4/4/dc44a3/photofunky.gif);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  position: relative;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:azure;
}
</style>
