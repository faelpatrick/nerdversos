<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
      <img src="/public/logo01.webp" class="logo" alt="Vite logo" />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
  border-radius: 50%;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
