<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue' 

export default {
  name: 'App',
  components: {
    HelloWorld
  }
};

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
h1 {
    display: flex;
    align-self: center;
    justify-content: center;    
    font-family: Avenir, Helvetica, Arial, sans-serif;
    color:azure;

}

body{
  background: linear-gradient(180deg, #000028 0%, #009999 100%);
    background-image: linear-gradient(rgb(0, 0, 40) 0%, rgb(0, 153, 153) 100%);
    background-position-x: initial;
    background-position-y: initial;
    background-size: initial;
    background-attachment: initial;
    background-origin: initial;
    background-clip: initial;
    background-color: initial;
}
</style>
