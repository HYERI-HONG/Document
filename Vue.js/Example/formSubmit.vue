<template>
<!-- submit.prevent = event.preventDefault()-->
  <form v-on:submit.prevent="submitForm">
    <div>
      <label for="username">ID : </label>
      <input id="username" type="text" v-model="username">
    </div>
    <div>
      <label for="password">Password : </label>
      <input id="password" type="password" v-model="password">
    </div>
    <button type="submit">login</button>
  </form>
</template>

<script>
import axios from 'axios'

export default {
  name: 'HelloWorld',
  data : function () {
    return {
      username : '',
      password : ''
    }
  },
  methods : {
    submitForm : function(){
        var url = 'https://jsonplaceholder.typicode.com/users'
        var data = {
          username : this.username,
          password : this.password
        }
        axios.post(url, data)
        .then(function(response) {
          console.log(response)
        }).catch(function(error) {
          console.log(error)
        })

    }
  }
}
</script>

<style scoped>
</style>
