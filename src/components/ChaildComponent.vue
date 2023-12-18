<template>
  <div>
    <slot :first-name="firstName" :last-name="lastName" />
  </div>
</template>
<script setup>
import { ref } from "vue";
const firstName = ref("Michael");
const lastName = ref("Hoffmann");
</script>
