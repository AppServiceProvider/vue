<template>
    <div>
      <h1>Hello user2</h1>
      <input type="text" v-model="name">
    </div>
  </template>
  
  <script>
    export default{
      name: 'ChildTwo',
      data(){
        return {
          name: ''
      }
    }
  }
  </script>
  