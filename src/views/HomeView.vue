<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import HeaderComponent from '../components/HeaderComponent.vue'
document.title = "Home"
</script>

<template>
  <HeaderComponent/>
  <main>
    <TheWelcome />
  </main>
</template>
