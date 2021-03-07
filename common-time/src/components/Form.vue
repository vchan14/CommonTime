<template>
  <div class="form">
    <form action="/action_page.php">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label>
        <input type="text" id="email" name="email"><br><br>
        <label for="lname">Code:</label>
        <input type="text" id="code" name="code"><br><br>
        <input type="submit" value="Submit">
    </form>   

    <Invitees />

  </div>
</template>

<script>
import Invitees from  './Invitees.vue'
export default {
  name: 'Form',
  components: {
    Invitees, 
  },
  props: {
    msg: String
  }
}
</script>
