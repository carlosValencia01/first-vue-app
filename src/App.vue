<script setup>
const name = 'Vue dinamico';
const arrayFrutas = ["Apple","Banana","Melon","Strawberry","Cherry"];
</script>

<template>
  <h1>Hola Mundo Vue JS</h1>
  <br>
  <p>{{name}}</p>
  <br>
  <ul>
    <li
      v-for="item in arrayFrutas"
    >
      {{item}}
    </li>
  </ul>
</template>
    
<style>
h1{
  color: red;
}
</style>