<template>
  <div class="hello container">
    <div class="row"> 
      <h3> Pick the date </h3>
    </div>
    <div class="row">
      <label for="date">Date:</label>
      <textarea id="date" name="date" rows="4" cols="50">    
        eg: [[02, 29], [03, 20]] - a list of dates [month, date]
      </textarea>

    </div>
  </div>  
    <!--
    <div class="alert alert-primary" role="alert">
      This is a primary alert—check it out!
    </div>

    <md-button class="md-raised md-primary">Click Me!</md-button>

    -->
</template>

<script>
import Vue from 'vue'
import { MdButton, MdContent, MdTabs } from 'vue-material/dist/components'
import 'vue-material/dist/vue-material.min.css'
import 'vue-material/dist/theme/default.css' 

Vue.use(MdButton)
Vue.use(MdContent)
Vue.use(MdTabs)

export default {
  name: 'Calendar',
}
</script>


<style scoped>




</style>