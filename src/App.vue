<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import ExtraMile from './components/ExtraMile.vue'
</script>

<template>
  <div>
    <a href="https://venezuela.un.org" target="_blank">
      <img src="/venezuelaFlag.svg" class="logo" alt="Vite logo" />
    </a>
  </div>
  <ExtraMile msg="Emissions for Sustainable Development of Nations Scale (ESDN Scale)" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
