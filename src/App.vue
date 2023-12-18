<template>
  <ChildComponent>
    <template v-slot:header>
      <h1>Lorem ipsum .</h1>
    </template>
    <template v-slot:footer>
      <span>dolor sit amet</span>
    </template>
    <p>aaaaaa</p>
  </ChildComponent>
</template>
<script>
import ChildComponent from "./components/ChildComponent.vue";
export default {
  name: "App",
  components: {
    ChildComponent,
  },
  data() {
    return {
      myVariable: `Parent Variable`,
    };
  },
};
</script>
<style></style>
