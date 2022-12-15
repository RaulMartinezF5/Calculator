<script setup>
import { ref, onMounted } from "vue";

// const screen = ref();

// onMounted(() => {
//   const screen = document.getElementById("screen");
//   console.log(screen);

//   const button = document.querySelectorAll(".calculator__button");
//   console.log(button);
//   button.forEach((el) => {
//     el.addEventListener("click", () => {
//       screen.textContent += el.textContent;
//     });
//   });
// });
</script>

<template>
    <button class="calculator__button divisas">€</button>

    <button class="calculator__button divisas">$</button>

    <button class="calculator__button divisas">¥</button>

    <button class="calculator__button divisas">L</button>

    <button class="calculator__button">MR</button>

    <button class="calculator__button">MC</button>

    <button class="calculator__button">M+</button>

    <button class="calculator__button operators">/</button>

    <button class="calculator__button">7</button>

    <button class="calculator__button">8</button>

    <button class="calculator__button">9</button>

    <button class="calculator__button operators">X</button>

    <button class="calculator__button">4</button>

    <button class="calculator__button">5</button>

    <button class="calculator__button">6</button>

    <button class="calculator__button operators">-</button>

    <button class="calculator__button">1</button>

    <button class="calculator__button">2</button>

    <button class="calculator__button">3</button>

    <button class="calculator__button operators">+</button>

    <button class="calculator__button">0</button>

    <button class="calculator__button">,</button>

    <button class="calculator__button">DEL</button>

    <button class="calculator__button operators">=</button>

</template>

<style lang="scss">
.calculator__button {
  color: rgba(255, 255, 255, 0.589);
  width: 3em;
  height: 2em;
  background-color: rgb(74, 76, 80);
  font-size: 2em;
  cursor: pointer;
  
  &:hover {
    opacity: 0.7;
  }
}

.operators {
  background-color: rgb(255, 145, 0);
}

.divisas {
  background-color: greenyellow;
}
</style>
