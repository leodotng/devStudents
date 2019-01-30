<template>
  <div id="app">
    <img alt="Vue logo" id="logo" src="./assets/logo.png">
    <HelloWorld msg="devStudents.org"/>
    <vs-button color="primary" type="filled">Primary</vs-button>
    <vs-button color="success" type="filled">Success</vs-button>
    <vs-button color="danger" type="filled">Danger</vs-button>
    <vs-button color="warning" type="filled">Warning</vs-button>
    <vs-button color="dark" type="filled">Dark</vs-button>
    <vs-button color="rgb(134, 4, 98)" type="filled">RGB</vs-button>
    <vs-button disabled type="filled">Disabled</vs-button>
    <vs-button color="primary" type="filled" to="/components/list.html">Router</vs-button>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#logo {
  height: 100px;
  width: 500px;
}
</style>
