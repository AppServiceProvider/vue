<template>
    <div>
      <h1>Component A</h1>
      <h3>component A props: {{ name }}</h3>
      <ComponentB/>
    </div>
  </template>
  <script>
  import ComponentB from "./ComponentB.vue";

  export default {
    name: "ComponentA",
    components: {
      ComponentB,
    },
    props: {
        name: String
      }
  };
  </script>
  