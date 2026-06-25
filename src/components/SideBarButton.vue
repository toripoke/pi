<script setup lang="ts">
const emit= defineEmits<{
    (e: 'click',label:string):void
}>()
const props= defineProps<{
    label: string
}>()
</script>

<template>
    <div class="button" @click="emit('click',props.label)">
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
    font-size: 30px;
}
</style>