<template>
  <div style="background-color: brown;">
    <p>This is the child component.</p>
    <slot></slot>
  </div>
</template>
<script>
export default {
  name: "ChildComponent",
};
</script>
