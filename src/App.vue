<template>
  <button @click="activeTab = 'ChildOne'">tab A</button>
  <button @click="activeTab = 'ChildTwo'">tab B</button>
  <button @click="activeTab = 'ChildThree'">tab C</button>



  <ChildOne v-if="activeTab === 'ChildOne'" />
  <ChildTwo v-if="activeTab === 'ChildTwo'" />
  <ChildThree v-if="activeTab === 'ChildThree'" />

</template>

<script >
import ChildOne from "./components/ChildOne.vue";
import ChildTwo from "./components/ChildTwo.vue";
import ChildThree from "./components/ChildThree.vue";


export default {
  name: "App",
  components:{
        ChildOne,
        ChildTwo,
        ChildThree,

    },
    data(){
        return{
          activeTab: 'ChildOne',
      }
  }
}
</script>

<style></style>
