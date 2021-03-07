<template>
  <div id="invitees">

    <p> Invitees' emails </p>
    <div class="input-group mb-3">
        <div class="input-group-prepend">
            <span class="input-group-text" id="inputGroup-sizing-default">Add</span>
        </div>
        <input type="text" class="form-control" aria-label="Default" aria-describedby="inputGroup-sizing-default">
    </div>
    <li v-for="invitee in invitees">
      <span class="id">{{ inviteee.id }}</span>
      <span class="email">£{{ product.email }}</span>
    </li>
  </div>
</template>

<script>

export default {
  name: 'Invitees',
  computed: {
      invitees(){
          return this.$store.state.invitees;
      },

  },
 
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
