<script setup lang="ts">
import { onMounted } from "vue";
// @ts-ignore
import { startGame } from "./game.js";

onMounted(() => {
  startGame();
});
</script>

<template>
  <div id="divInfo">
    drag and drop <a href="https://www.mixamo.com/" target="_blank" rel="noopener noreferrer">mixamo</a> animation
    (.fbx)<br />
  </div>
</template>

<style scoped>
#divInfo {
  padding: 8px;
  position: fixed;
  background: white;
}
</style>
