<script setup></script>
<template>
    <button><div class=circle></div></button>
</template>



<style lang="scss" scoped>
button {

.circle::before {
    background-color: rgb(114, 3, 35);
  content: "+";
  height:2vh;
  width:2vh;
  font-size:5vh;
  display:flex;
  flex-direction:row;
  align-items:center;
  justify-content:center;
  font-weight:bold;
  font-family:courier;
  color:white;
}
    padding: 8px 16px;
    border: none;
    background-color: rgb(114, 3, 35);
  }
</style>