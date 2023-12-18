<template>
  <ChildComponent :parentClass="propsInClass.pink" />
  <ChildComponent :parentClass="propsInClass.blue" />
</template>

<script>
import ChildComponent from "./components/ChildComponent.vue";

export default {
  data() {
    return {
      propsInClass: {
        pink: "pink",
        blue: "blue",
      },
    };
  },
  components: {
    ChildComponent,
  },
};
</script>
<style>
.pink {
    background-color: DeepPink;
}
.blue {
    background-color: DeepSkyBlue;
}
</style>
