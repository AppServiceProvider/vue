<script >
import ComponentA from "./components/ComponentA.vue";

export default {
  components: {
    ComponentA,
  },
  provide:{
    userName: "roman hossain shaon"
  }
};
</script>

<template>
  <h1>App vue</h1>
  <ComponentA name="dataPass App.vue"/>
</template>

