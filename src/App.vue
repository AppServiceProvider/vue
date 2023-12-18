<template>
  <ChildComponent v-slot="slotProps">Name: {{ slotProps.firstName }} {{ slotProps.lastName }}</ChildComponent>
</template>
<script>
import ChildComponent from "./components/ChaildComponent.vue";
export default {
  name: "App",
  components: {
    ChildComponent,
  },
};
</script>
<style></style>
