<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <pageHeader />
    <pageBody />
    <pageFooter />
  </div>
</template>

<script>

import pageHeader from './components/header.vue';
import pageFooter from './components/footer.vue';
import pageBody from './components/body.vue';

export default {
  name: 'App',
  components: {
    pageHeader,
    pageFooter,
    pageBody
  }
}
</script>

<style>
body{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
 
}
a{
  color: white;
}
</style>
