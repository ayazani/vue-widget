<script setup lang="ts">

</script>

<template>
<button class="button"><slot name="icon"/> <slot /></button>
</template>

<style scoped>

.button {
  border: none;
  border-radius: 10px;
  font-weight: 500;
  font-size: 20px;
  line-height: 40px;
  background: var(--gradient);
  color: inherit;
  cursor: pointer;
  &:hover {
   background: var(--gradient-inverted);
  }
}
</style>