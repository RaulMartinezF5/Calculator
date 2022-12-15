<script>
import Screen from './components/Screen.vue';
import Buttons from './components/buttons.vue';
export default{
  name:"App",
  components:{
    Screen,
    Buttons
  }
}
</script>

<template>
<div class="calculator">
 <Screen/>
 <Buttons/>
</div>
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
  background-color: rgba(37, 37, 65, 0.706);
}
.calculator {
  display: grid;
  grid-template-columns: repeat(4,1fr);
  grid-template-rows: repeat(7,1fr);
  height: 90vh;
  gap: 1.3em;
  background-color: rgb(43, 41, 41);
  padding: 1.5em;
  }
</style>
