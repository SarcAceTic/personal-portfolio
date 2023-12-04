<script setup></script>

<template>
  <v-container>
    <section>
      <v-row class="justify-center" no-gutters>
        <span class="my-2 grad-border">
          <v-avatar size="85" class="main-avatar" image="/myPFP.jpg"></v-avatar>
        </span>
        <div class="d-flex flex-column">
          <h1 class="text-purple-accent-3 text-center mb-1">SarcAceTic / Zhell</h1>
          <span class="text-center mb-1">
            A younglin learning the ropes of the world AND front-end engineering!
          </span>
        </div>
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
