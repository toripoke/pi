<script setup lang="ts">
const props= defineProps<{
    label: string
}>()

const loglabel = () =>{
    console.log(props.label)
}

</script>

<template>
    <div class="button" @click="loglabel">
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