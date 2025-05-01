<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import Header from './components/Header.vue'
import AboutMe from './components/AboutMe.vue'
</script>

<template>
  <div class="bg-gray-50 w-full h-full min-h-screen flex justify-center">
    <div class="w-3/5 flex flex-row justify-center pt-28">
      <Header />
      <div class="w-1/2">
        <AboutMe />
      </div>
    </div>
  </div>
</template>
