<template>
  <div>
    <h2>{{ title }} {{ likes }} {{ description }}</h2>
    <h2 v-bind="$attrs">{{ title }} {{ likes }} {{ description }}</h2>
    <h2>{{ title }} {{ likes }} {{ description }}</h2>
    <h2>{{ title }} {{ likes }} {{ description }}</h2>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    likes: Number,
    description: {
      type: String,
      required: true,
      default: "props missing",
    },
  },
  inheritAttrs:false,
};
</script>
