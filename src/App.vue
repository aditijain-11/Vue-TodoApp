<script setup>
import { RouterView } from 'vue-router';
import TodoHeader from "./components/TodoHeader.vue";
</script>

<template>
  <TodoHeader />
  <RouterView />
</template>

<style lang="scss">


* {
// font-family: 'Playfair', serif;
// font-family: 'Rubik', sans-serif;
//   font-family: "Rubik", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  color: white;
  background-color: rgb(27, 29, 43);
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
