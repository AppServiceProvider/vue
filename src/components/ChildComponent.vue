<template>
  <div id="card-content">
          <slot name="header"></slot>
          <slot name="footer"></slot>
  </div>
</template>
<script>
export default {
  name: "ChildComponent",
};
</script>
