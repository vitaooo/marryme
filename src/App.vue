
<template>
  <AppHeader
  v-show="showHeader"
  >

 </AppHeader> 
  <img alt="Vue logo" src="./assets/logo.png">
  <h2>to ficando maluco</h2>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import AppHeader from './components/AppHeader.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    AppHeader
  },
  data() {
    return {
      showHeader: true
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
