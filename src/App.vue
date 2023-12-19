<template>
  <button @click="activeTab = 'TabA'">tab A</button>
  <button @click="activeTab = 'TabB'">tab B</button>
  <button @click="activeTab = 'TabC'">tab C</button>

  <ChaildOne v-if="activeTab === 'TabA'" />
  <ChaildTwo v-if="activeTab === 'TabB'" />
  <ChaildThree v-if="activeTab === 'TabC'" />
</template>

<script >
import ChaildOne from "./components/ChaildOne.vue";
import ChaildTwo from "./components/ChaildTwo.vue";
import ChaildThree from "./components/ChaildThree.vue";


export default {
  name: "App",
  components:{
        ChaildOne,
        ChaildTwo,
        ChaildThree,

    },
    data(){
        return{
          activeTab: 'TabA',
      }
  }
}
</script>

<style></style>
