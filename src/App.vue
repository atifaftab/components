<template>
  <Greet :name="name" :heroName/>
  <CallIn :hero="hero"/>

</template>

<script>
import Greet from './components/Greet.vue';
import CallIn from './components/CallIn.vue';
export default {
  name: 'App',
  components :{
    Greet,
    CallIn
  },
  data(){
    return{
      name : 'bruce',
      hero : 'Thor',
      batman : 'BATMAN',
      newHero : 'Spiderman'
    }
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
