<script setup>
import HeaderComp from "./components/template/HeaderComp.vue";
import RodapeComp from "./components/template/RodapeComp.vue";
</script>

<template>
  <HeaderComp />
  <RouterView />
  <RodapeComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /*padding: 2rem;*/
  height: 100vh;

  font-weight: normal;
}
header {
  background-color: rgba(140, 0, 255, 0.75);
  color: rgb(240, 235, 244);
  height: 10%;
  font-size: 1.3rem;
  display: flex;
}
footer {
  background-color: rgba(140, 0, 255, 0.75);
  color: rgb(240, 235, 244);
  height: 10%;
  font-size: 1.3rem;
}
main {
  height: 80%;
  background-color: rgba(140, 0, 255, 0.156);
  color: rgba(45, 1, 81, 0.794);
}
</style>
