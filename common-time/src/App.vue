<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Common Time"/>
    <div class="container">
      <div class="row">
        <div class="col-4"> <Form/> </div>
        <div class="col-8"> <Calendar/> </div>
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Calendar from './components/Calendar.vue'
import Form from './components/Form.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    Calendar, 
    Form
  }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
  color: #2c3e50;