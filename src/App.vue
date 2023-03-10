<template>
  <div id="app">
    <NextTick />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import NextTick from './components/NextTick.vue';
export default {
  name: 'App',
  components: {
    HelloWorld,
    NextTick,
  },
};
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
