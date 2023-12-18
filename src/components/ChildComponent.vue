<template>
 <div :class="parentClass" class="other-class"><h1>Lorem ipsum dolor sit amet.</h1></div>
</template>

<script>
export default {
  props: ["parentClass"],
}
</script>