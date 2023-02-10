<script setup lang="ts">
// import ButtonComponents from "../components/ButtonComponents.vue";
import CardComponents from "../components/CardComponents.vue";
import HeaderComponents from "../components/HeaderComponents.vue";
import InputComponents from "../components/InputComponents.vue";
</script>

<template>
  <HeaderComponents />
  <main class="container"></main>
  <InputComponents />
  <CardComponents />
</template>
<style scoped>
.container {
  width: 100%;
  height: 100%;
  background-image: url("../assets/img/fundopoke.jpg");
  background-repeat: repeat-x;
  position: absolute;
  top: 100px;
  z-index: 0;
  background-size: contain;
  background-size: cover;
  min-width: 394px;
  
}
</style>
