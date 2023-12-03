<script setup>
const contacts = [
  { name: 'mdi-github', href: 'https://github.com/SarcAceTic' },
  { name: 'mdi-twitter', href: 'https://twitter.com/SarcAce33749' },
  { name: 'mdi-youtube', href: 'https://www.youtube.com/channel/UC3f4hB4foeVvAR-Kk2k2vCQ' }
]
</script>

<template>
  <v-footer class="pa-4 d-flex flex-column">
    <div><v-btn class="mx-4" icon color="transparent" elevation="0" v-for="contact in contacts"><v-icon size="25">{{ contact.name }}</v-icon></v-btn></div>
   <p class="text-grey">Made with Vuetify 3 and Vite 3</p>
  </v-footer>
</template>
