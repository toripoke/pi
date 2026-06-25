<script setup lang="ts">

import SideBarButton from './SideBarButton.vue'

const fruit=defineModel<string>('fruit')
const handleClick=(label: string)=>{
    fruit.value=label
    console.log(label)
}

</script>

<template>
    <div class="sidebar">
       <SideBarButton @click="handleClick" label="Apple"/>
       <SideBarButton @click="handleClick" label="Banana"/>
       <SideBarButton @click="handleClick" label="Orange"/>
       <SideBarButton @click="handleClick" label="Lemon"/>
    </div>
</template>

<style scoped>
.sidebar{
    width: 300px;
    background-color: #eeeeee;
    display: flex;
    flex-direction: column;
    justify-content: center;
}



</style>