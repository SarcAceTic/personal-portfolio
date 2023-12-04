<script setup>
const contacts = [
  { name: 'mdi-github', href: 'https://github.com/SarcAceTic', user: 'SarcAceTic' },
  { name: 'mdi-twitter', href: 'https://twitter.com/SarcAce33749', user: 'SarcAce33749' },
  {
    name: 'mdi-youtube',
    href: 'https://www.youtube.com/channel/UC3f4hB4foeVvAR-Kk2k2vCQ',
    user: 'SarcAceTic'
  }
]
</script>

<template>
  <v-container>
    <section>
      <h2 class="mb-4 text-center text-purple-accent-3">My Contacts</h2>
      <v-row justify="center" no-gutters>
        <v-col cols="7" class="my-2 text-center" v-for="contact in contacts">
          <v-btn :href="contact.href" variant="outlined" target="_blank" class="w-100 text-none" size="large">
            <v-icon class="mr-2" size="33">{{ contact.name }}</v-icon>
            <p>{{ contact.user }}</p>
           
          </v-btn>
        </v-col>
        <v-col cols="11" sm="7" class="my-2 text-center">
          <v-btn class="w-100 text-none" variant="outlined" size="large">
            <v-icon class="mr-2" size="33">mdi-gmail</v-icon>
            <p>sarcacetic@gmail.com</p>
          </v-btn>
        </v-col>
      </v-row>
    </section>
  </v-container>
</template>

<style scoped>
</style>
