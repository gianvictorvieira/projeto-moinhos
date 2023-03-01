<template>
  <Inicio/>
  <div class="bg-dark"></div>
</template>

<script>
import Inicio from './components/IndexHome.vue'

export default {
  name: 'App',
  components: {
    Inicio
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000;
  width: 100%;
  height: 100%;
}
</style>
