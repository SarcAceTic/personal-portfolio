<script setup>
import { useDisplay } from 'vuetify';

const {lg, xl, xxl, xlAndUp } = useDisplay();
</script>

<template>
  <v-container>
    <section>
      <v-row class="justify-center" no-gutters>
        <v-col class="my-2 text-center" cols="12">
          <span class="grad-border">
            <v-avatar size="85" class="main-avatar" image="/myPFP.jpg"></v-avatar>
          </span>
        </v-col>
        <v-col cols="12">
          <div class="d-flex flex-column">
            <h1 class="text-purple-accent-3 text-center mb-1">SarcAceTic / Zhell</h1>
            <span :class="{'lg-p-size': lg, 'xl-p-size': xl, 'xxl-p-size': xxl}" class="text-center mb-1">
              A younglin learning the ropes of the world AND front-end engineering!
            </span>
          </div>
        </v-col>
      </v-row>
    </section>
  </v-container>
</template>

<style scoped>
.grad-border {
  display: inline-block;
  width: auto;
  height: 100%;
  background: -webkit-linear-gradient(left top, purple 0%, rgb(76, 0, 255) 100%);
  border-radius: 1000px;
  padding: 3px;
}
</style>
