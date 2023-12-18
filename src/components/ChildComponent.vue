<template lang="html">
  <button type="button" @click="passEvent">Update me</button>
</template>

<script>
export default {
  name: "ChildComponent",
  methods: {
    passEvent() {
      this.$emit("changeTitle", "Awesome ");
    },
  },
};
</script>

<style lang="css" scoped></style>
