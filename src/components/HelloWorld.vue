<!-- <script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script> -->

<script>
export default{
  props:[
    'name',
    'heroName',
  ]
}
</script>

<template>
  <div>
    <h2>{{ name }} {{ heroName }}</h2>
  </div>
</template>

<style scoped></style>
