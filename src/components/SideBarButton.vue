<script setup lang="ts">
defineProps<{
    label: string
}>()
</script>

<template>
    <div class="button">
        <div class="buttontext">{{label}}</div>
    </div>
</template>

<style scoped>
.button {
    display: flex;
    align-items: center;
    height: 60px;
    /* border: 1px solid red; */
}

.buttontext{
    width: 100%;
    text-align: center;
}
</style>