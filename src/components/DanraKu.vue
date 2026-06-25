<script setup lang="ts">
defineProps<{
    fruit: string
}>()
</script>

<template>
  <div class="syoumozi">
    {{ `${fruit} `.repeat(20) }}
  </div>
</template>

<style scoped>
.syoumozi {
    font-size:15px;
}
</style>