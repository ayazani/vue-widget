<script setup lang="ts">
import Button from "./components/Button/Button.vue";
import WidgetPanel from "@/components/WidgetPanel.vue";
</script>

<template>
  <main class="main">
    <WidgetPanel />
  </main>
</template>

<style scoped>
.main {
  height: 100vh;
  width: 100vw;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
