<script setup lang="ts">
import SideBarButton from './SideBarButton.vue'
</script>

<template>
    <div class="sidebar">
       <SideBarButton label="Apple"/>
       <SideBarButton label="Banana"/>
       <SideBarButton label="Orange"/>
       <SideBarButton label="Lemon"/>
       <SideBarButton />
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