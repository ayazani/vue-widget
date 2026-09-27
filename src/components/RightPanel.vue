<script setup lang="ts">
import StatDesc from "@/components/StatDesc.vue";
import ChangeCity from "@/components/ChangeCity.vue";

const data = {
  humidity: {
    label: "humidity",
    value: "90%",
  },
  precipitation: {
    label: "precipitation",
    value: "0%",
  },
  wind: {
    label: "wind",
    value: "3 m/h",
  }
}
</script>

<template>
  <div class="right-panel">
<div class="right-panel-titles">
  <StatDesc v-bind="data.humidity" />
  <StatDesc v-bind="data.precipitation" />
  <StatDesc v-bind="data.wind" />
</div>
  <div>карты</div>
  <ChangeCity />
  </div>
</template>

<style scoped>
.right-panel {
  display: flex;
  flex-direction: column;
  justify-content: space-around;

}
.right-panel-titles {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
</style>