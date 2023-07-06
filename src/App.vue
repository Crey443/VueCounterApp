<script setup>
import { ref } from "vue";
const counter = ref(0);
</script>

<template>
  <main>
    <div>
      <h4>The cound is...</h4>
      <h1>{{ counter }}</h1>
      <button @click="counter--">-</button>
      <button @click="counter++">+</button>
    </div>
  </main>
</template>

<style scoped>
main {
  height: 100vh;
  width: 100vw;
  display: flex;
  align-content: center;
  justify-content: center;
}

div {
  text-align: center;
}
</style>
