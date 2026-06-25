<script setup lang="ts">
defineProps<{
  color: string
}>()
</script>

<template>
  <div class="square">
  </div>
</template>

<style scoped>
.square {
    width: 200px;
    height: 200px;
    background-color: v-bind(color);
    border-radius: 20px;
}
</style>