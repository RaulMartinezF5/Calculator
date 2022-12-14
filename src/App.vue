<script>
import Calculator from './components/Calculator.vue';
export default{
  name:"App",
  components:{
    Calculator
  }
}
</script>

<template>
 <Calculator/>
 
</template>

<style>
body {
  margin:0;
  padding: 0;
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
</style>
