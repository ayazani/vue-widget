<script setup lang="ts">
import Button from "@/components/Button/Button.vue";
import LocationIcon from "@/components/Icons/LocationIcon.vue";
</script>

<template>
  <div class="change-city">
  <Button> <template #icon> <LocationIcon />
  </template>Change city</Button>
  <input />
  <Button>Save</Button>
  </div>
</template>

<style scoped>
.change-city {
  display: flex;
  flex-direction: row;
  gap: 0;
}
</style>