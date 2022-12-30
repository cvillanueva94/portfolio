<script setup>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div class="bg-slate-800 bg-contain bg-auto h-screen">
    <div class="flex ...">
      <div class="flex-none w-14 h-14 ...">
      </div>
      <div class="grow h-14 ...">
        <NavBar/>
        <HelloWorld/>
        <Footer/>
      </div>
      <div class="flex-none w-14 h-14 ...">
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>

