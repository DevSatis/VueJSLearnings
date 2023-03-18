<template>
  <div>
   <Greet name = "Satish"  heroName = "Sintu"/>
   <Greet name = "Dev" heroName="Dwit" />
   <Greet name = "Kumar" heroName="Darling"/>
   <Greet :name = "name" :heroName= "channel"/>
   <Test />
  </div>
   
</template>

<script >
 import Greet from "./components/Greet.vue"; 
 import Test from "./components/Test.vue";

 export default{
  name: "App",
  components:{
    Greet,
    Test,
  },
  data(){
    return {
      name:"Satish", 
      channel: "True Coder"
    }
  }
 }
</script>

