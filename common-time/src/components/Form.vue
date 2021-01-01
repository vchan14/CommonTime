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
  </div>
</template>

<script>
export default {
  name: 'Form',
  props: {
    msg: String
  }
}
</script>