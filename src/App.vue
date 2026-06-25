<script setup lang="ts">
import SampleComponent from './components/SampleComponent.vue'
import SideBar from './components/SideBar.vue'
import WelcomeMessage from './components/WelcomeMessage.vue'
import MainContent from './components/MainContent.vue'
</script>

<template>
  <main>
    <div class="horizontal">
      <SideBar />
      <MainContent/> 
      <!-- <WelcomeMessage msg="Webエンジニアになろう講習会へようこそ" /> -->
      <!-- <SampleComponent msg="Webエンジニアになろう講習会へようこそ" /> -->
    </div>
  </main>
</template>

<style scoped>

.horizontal{
  display : flex;
  flex-direction : row;
  /* border :1px solid red; */
  height: 100vh;
  
}
</style>
