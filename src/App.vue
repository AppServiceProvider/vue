<template>
  <ChildComponent :childProp='parentData'></ChildComponent>
</template>

<script>
import ChildComponent from './components/ChildComponent.vue';

export default {
  data(){
      return {
          parentData:'App.vue component'
          }
  },
  components:{
      ChildComponent
  }
}
</script>
