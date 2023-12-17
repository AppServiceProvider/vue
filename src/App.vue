<template>
    <HelloWorld name="roman" heroName="superMan"/>
    <HelloWorld name="hossain" heroName="batMan"/>
    <HelloWorld :name="name" :heroName="channel"/>

    <Artical title="Artical title" :likes="500" description="lorem imsum" />

</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Artical from './components/Artical.vue';

export default{
  components:{
    HelloWorld,
    Artical
  },
data() {
  return {
    name:"github",
    channel: "opensource"
  }
},
}
</script>