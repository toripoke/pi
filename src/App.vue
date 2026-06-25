<script setup lang="ts">
import SideBar from './components/SideBar.vue'
import SampleComponent from './components/SampleComponent.vue'
import WelcomeMessage from './components/WelcomeMessage.vue'

</script>

<template>
  <main>
    <div class="horizontal">
      <SideBar />
      <WelcomeMessage msg="Webエンジニアになろう講習会へようこそ" />
      <SampleComponent msg="Webエンジニアになろう講習会へようこそ" />
    </div>
  </main>
</template>

<style scoped>
main {
  padding: 2rem;
}

.horizontal{
  display : flex;
  flex-direction : row;
}
</style>
