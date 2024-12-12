<script setup lang="ts">
import useBoolean from '@relaxed/hook'
const { bool,toggle } = useBoolean()
</script>

<template>
  <div>
    <h1>Hello World Blog useBoolean {{ bool }}  </h1>
    <d-button type="info" @click="toggle"> Toogle </d-button>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
