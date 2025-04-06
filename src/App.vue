
<template>
  <AppHeader
  v-show="showHeader"
  >

 </AppHeader> 
  <img alt="Vue logo" src="./assets/logo.png">
  <h2>to ficando maluco</h2>
  <PicsComponent>
  </PicsComponent>
  
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import PicsComponent from './components/PicsComponent.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    PicsComponent
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
