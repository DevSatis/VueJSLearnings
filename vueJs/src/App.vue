<template>
  <div>
   <Greet />
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

  }
 }
</script>

