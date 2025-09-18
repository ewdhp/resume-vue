<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
      <nav>
        <RouterLink to="/"></RouterLink>
        <RouterLink to="/about"></RouterLink>
      </nav>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
