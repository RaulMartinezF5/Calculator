<script setup>

</script>

<template>
<div class="calculator">
<div class="calculator__screen">

</div>
<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>

<button class="calculator__button">
  
</button>

<button class="calculator__button">

</button>
</div>
</template>

<style lang="scss">


.calculator {
  display: grid;
  grid-template-columns: repeat(4,1fr);
  grid-template-rows: repeat(7,1fr);
  height: 70vh;
  width: 60%;
 gap: 2em;

&__screen{
  grid-column: 1/5;
  background-color: green;
  height: 10em;
}

  &__button{
    width: 12em;
    height: 8em;
    background-color: red;
  }
}
</style>
