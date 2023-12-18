<template>
  <div>
    <p>This is the parent component.</p>
    <ChildComponent>
      <p>This is injected content from the parent component.</p>
      <p>It can still bind to data in the parent's scope: {{myVariable}}</p>
    </ChildComponent>
  </div>
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
      myVariable: `Parent Variable`
    };
  },
};
</script>
<style></style>
