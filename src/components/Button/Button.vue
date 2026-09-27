<script setup lang="ts">

</script>

<template>
  <button class="button"><span class="button-content"><slot name="icon"/> <slot /></span></button>
</template>

<style scoped>

.button {
  border: none;
  border-radius: 10px;
  font-weight: 500;
  font-size: 20px;
  line-height: 40px;
  padding: 5px;
  background: var(--gradient);
  color: inherit;
  cursor: pointer;
  &:hover {
   background: var(--gradient-inverted);
  }
}

.button-content {
  display: flex;
  flex-direction: row;
  align-content: center;
  align-items: center;
  justify-content: center;
  width: 100%;
  gap: 16px;
}
</style>