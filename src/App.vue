<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './layout/Header.vue'
import Footer from './layout/FooterNav.vue'
</script>

<template>
  <v-app>
    <Header />
    <v-main>
      <RouterView />
    </v-main>
    <Footer />
  </v-app>
</template>

<style scoped></style>
