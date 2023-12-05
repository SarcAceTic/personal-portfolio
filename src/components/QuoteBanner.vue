<script setup></script>

<template>
  <div class="image-container">
    <v-img class="banner-image w-100 h-auto" src="/bannerimage.png" />
    <p class="w-75 text-center quote-text"><i>"Your time is limited, don't waste it living someone else's life."</i><br>- Steve Jobs</p>
  </div>
</template>

<style scoped>
.image-container {
  position: relative;
  background: rgb(54, 11, 73);
  background: linear-gradient(0deg, rgba(54, 11, 73, 1) 0%, rgba(98, 18, 172, 1) 100%);
}
.banner-image {
  position: relative;
  opacity: 0.35;
  display: block;
}
.quote-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  animation-duration: 3s;
  animation-name: slide-bottom;
}
@keyframes slide-bottom {
  from {
    margin-left: 100%;
  }
  to {
    margin-left: 0%;
  }
}
</style>
