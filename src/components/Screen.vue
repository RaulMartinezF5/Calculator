<script setup>
import { ref, onMounted } from 'vue'

const screen = ref()

onMounted(() => {
 const screen = document.getElementById("screen");
 console.log(screen)

const button = document.querySelectorAll(".calculator__button");
console.log(button)
button.forEach(el=>{
  el.addEventListener("click",()=>{
    screen.textContent += el.textContent;
  })
})

})

</script>

<template>

<div id="screen" class="calculator__screen">
0
</div>

</template>

<style lang="scss">
.calculator__screen{
  display: flex;
  justify-content: end;
  align-items: center;
  grid-column: 1/5;
  background-color: rgba(0, 174, 255, 0.808);
  height: 3em;
  font-size: 2em;
  padding-right: 1em;
}
</style>
