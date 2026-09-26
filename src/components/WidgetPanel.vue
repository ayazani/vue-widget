<script setup lang="ts">

import Button from "@/components/Button/Button.vue";
import RightPanel from "@/components/RightPanel.vue";
</script>

<template>
  <div class="widget">
    <div class="panel" name="leftPanel">
      левая панель

    </div>
    <div class="panel" name="rightPanel">
      <RightPanel />
    </div>
  </div>
</template>

<style scoped>
.widget {
  background: var(--color-bg-main);
  width: 944px;
  height: 623px;
  border-radius: 25px;
  opacity: 1;
  display: flex;
  flex-direction: row;
}

.panel {
  width: 50%;
  height: 100%;
  padding: 20px;
}
</style>