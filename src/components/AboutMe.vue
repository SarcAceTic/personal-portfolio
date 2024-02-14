<script setup>
import { useDisplay } from 'vuetify';

const {lg, xl, xxl, xlAndUp } = useDisplay();
</script>

<template>
  <v-container>
    <section>
      <h2 class="text-purple-accent-3 text-center my-1">About Me</h2>
      <p :class="{'lg-p-size': lg, 'xl-p-size': xl, 'xxl-p-size': xxl}" class="text-center mx-sm-5 mx-md-15">
        Hi there! I'm an Indonesian teenager whose really passionate about front-end engineering and
        programming! I'm also open to learning new things, other than programming, such as Arts, and
        Mathematics!
      </p>
    </section>
  </v-container>
</template>

<style scoped></style>
