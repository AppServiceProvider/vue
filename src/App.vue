<template>
  <h1>{{ title }}</h1>
  <ChildComponent @changeTitle="ChangeT($event)" />
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
      title: "Rick Grimes",
    };
  },
  methods: {
    ChangeT(title) {
      this.title = title;
    },
  },
};
</script>
<style></style>
