<script>
import Home from './views/Home.vue';

export default{
  name: 'App',
  components: {
    Home
  }
}
</script>


<template>
    <div class="text-center py-5">
      <p class=" text-4xl uppercase">utility zones</p>
      <router-view/>
    </div>
    <Home/>
</template>
  

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
</style>