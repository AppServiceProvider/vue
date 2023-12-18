<template>
  <div>
    <h1>Component C</h1>
    <h3>component c props: {{ userName }}</h3>
  </div>
</template>

<script>
export default {
  name: "ComponentC",
  inject:["userName"]
};
</script>
