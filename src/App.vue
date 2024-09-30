<script setup>
import HomeIndex from './pages/HomeIndex.vue'
import AppBar from './components/AppBar.vue'
</script>
<template>
  <v-app>
    <header>
      <AppBar />
    </header>

    <v-main>
      <HomeIndex />
    </v-main>
  </v-app>
</template>
