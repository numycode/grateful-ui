<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import BottomNav from './components/BottomNav.vue'

</script>

<template>
<v-app>
    <h1>Welcome</h1>
  <v-main>
    <RouterView />
  </v-main>
    <BottomNav />
  </v-app>
</template>

<style scoped>

</style>
