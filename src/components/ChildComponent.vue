<template>
  <p>{{ name }}</p>
  <p>{{ id }}</p>
  <p>{{ gender }}</p>
  <p>{{ age }}</p>
  <p>{{ like }}</p>
</template>

<script>
export default {
  props: ["name", "id", "gender", "age", "like"]
};
</script>
