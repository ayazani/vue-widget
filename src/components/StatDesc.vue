<script setup lang="ts">
const { label, value } = defineProps({
  label: String,
  value: String,
})
</script>

<template>
  <div class="widget-label">
    <span class="widget-label-text">
      {{label}}:
    </span>
    <span>
       {{value}}
    </span>
  </div>
</template>

<style scoped>
.widget-label {
  font-size: 28px;
  display: flex;
  flex-direction: row;
  width: 100%;
  justify-content: space-between;
}
.widget-label-text {
  font-weight: 700;
  text-transform: uppercase;
}
</style>