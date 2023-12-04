<script setup>
import QuoteBannerVue from '../components/QuoteBanner.vue'
import MainProfileVue from '../components/MProfile.vue'
import AboutMe from '../components/AboutMe.vue'
import MySkills from '../components/MySkills.vue'
import MyContacts from '../components/MyContacts.vue'
</script>

<template>
  <QuoteBannerVue />
  <MainProfileVue />
  <v-divider class="mx-4"></v-divider>
  <AboutMe />
  <v-divider class="mx-4"></v-divider>
  <MySkills /> 
  <v-divider class="mx-4"></v-divider>
  <MyContacts />
</template>

<style scoped>

</style>
