<template>
  <ChildComponent :childJimmy="jimmy"></ChildComponent>
</template>

<script>
import ChildComponent from "./components/ChildComponent.vue";

export default {
  data() {
    return {
      jimmy: {
        name: "Jimmy",
        id: 55688,
        gender: "male",
        age: 26,
        like: ["surfing", "diving", "climbing"],
      },
    };
  },
  components: {
    ChildComponent,
  },
};
</script>
<style>
</style>
