<template>
  <ChildComponent v-slot="slotProps">Name: {{ slotProps.firstName }} {{ slotProps.lastName }}</ChildComponent>
</template>
<script>
import ChildComponent from "./components/ChildComponent.vue";
export default {
  name: "App",
  components: {
    ChildComponent,
  },
};
</script>
<style></style>
