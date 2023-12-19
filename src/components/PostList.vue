<template>
    <div>
      <button @click="getPosts">load posts</button>
      <div v-for="post in posts" :key="post.id">
        <h3>{{ post.id }}.{{ post.title }}</h3>
        <p>{{ post.body }}</p>
        <hr />
      </div>
    </div>
  </template>
  
  <script>
  import axios from "axios";
  
  export default {
    name: "PostList",
    data() {
      return {
        posts: [],
      };
    },
    methods: {
      getPosts() {
        axios
          .get("https://jsonplaceholder.typicode.com/posts")
          .then((response) => {
            // Log the response data
            console.log(response.data);
            // Update the component's posts data property
            this.posts = response.data;
          })
          .catch((error) => {
            console.log(error);
          });
      },
    },
  };
  </script>
  
