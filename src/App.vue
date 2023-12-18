<template>
  <ChildComponent
    :name="jimmy.name"
    :id="jimmy.id"
    :gender="jimmy.gender"
    :age="bindOther"
    :like="bindOther"
  ></ChildComponent>
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
      bindOther: "bindOther",
    };
  },
  components: {
    ChildComponent,
  },
};
</script>
<style></style>
