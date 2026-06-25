<script setup lang="ts">
import {ref} from 'vue'
import SampleComponent from './components/SampleComponent.vue'
import SideBar from './components/SideBar.vue'
import WelcomeMessage from './components/WelcomeMessage.vue'
import MainContent from './components/MainContent.vue'
const fruit=ref('Apple')
</script>

<template>
  <main>
    <div class="horizontal">
      <SideBar v-model:fruit="fruit"/>
      <MainContent :fruit="fruit"/>
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
