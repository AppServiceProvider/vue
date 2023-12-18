<template>
  <p>{{ childJimmy.name }}</p>
  <p>{{ childJimmy.id }}</p>
  <p>{{ childJimmy.gender }}</p>
  <p>{{ childJimmy.age }}</p>
  <p>{{ childJimmy.like }}</p>
</template>

<script>
export default {
  props: ["childJimmy"],
};
</script>
