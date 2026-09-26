<script setup lang="ts">

import Button from "@/components/Button/Button.vue";
</script>

<template>
  <div class="right-panel">
<div>тайтл</div>
  <div>карты</div>
  <Button> <template #icon> +
  </template> Изменить город</Button>
  </div>
</template>

<style scoped>
.right-panel {
  display: flex;
  flex-direction: column;
  justify-content: space-around;

}
</style>