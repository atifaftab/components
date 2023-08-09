<template>
  <Call/>
  <Greet/>
</template>

<script>
import Greet from './components/Greet.vue';
import Call from './components/Call.vue';
export default {
  name: 'App',
  components :{
    Greet,
    Call
  }
}
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
