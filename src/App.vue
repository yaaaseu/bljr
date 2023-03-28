<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
    <HelloWorld msg="Hello"  />
    <tombol class="btn btn-success"/>
    
  </div>

  <div id="untuktelkom">
  <telkom />
  <img src="" alt="">
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import tombol from './components/tombol.vue';
import telkom from './components/telkom.vue';
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap/dist/js/bootstrap.js';


export default {
  name: 'App',
  components: {
    HelloWorld,
    tombol,
    telkom,
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

#untuktelkom {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  margin-top: 60px;
}


</style>
