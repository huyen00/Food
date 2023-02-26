<template>
  
  <div id="app fixed h-full" style="height:100%">
    <!-- <header /> -->
    <!-- <HomeGame /> -->
    <!-- <headerContact /> -->
    <!-- <listContact /> -->
    <foodHeader />
    <!-- <router-view></router-view>  -->
  </div>
</template>

<script>

import foodHeader from './components/foodHearder.vue'





export default {
  name: 'App',
 
  
  components: {
    
    
    foodHeader
  },
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
 
}
</style>
