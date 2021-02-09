<template>
  <div id="app">
    <!--<marquee><img alt="Vue logo" src="./assets/logo.png"></marquee>-->
    <HelloWorld msg="Department"/>
  
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
//
import HelloWorld from './components/EmployeeForm.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
  margin-top: 0px;
}
</style>
