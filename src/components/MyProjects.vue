<script setup>
import { useDisplay } from 'vuetify';

const {mdAndDown, lg, xl, xxl, xlAndUp } = useDisplay();
const projects = [
  {
    name: 'Pricing Project',
    description:
      "This is my very first serious project that I've worked on, and I took inspiration from Frontend Mentor! I took one of the challenges and made them in my own style!",
    link: 'https://sarcsprice.vercel.app/',
    glink: 'https://github.com/SarcAceTic/pricing-project',
    image: '/PricingProject.png'
  },
  {
    name: 'My Anime List Redesign',
    description:
      "This is my attempt on redesigning MyAnimeList. This project was the serious project that I've been wanting to make, just to test out my UI/UX skills and creativity!",
    link: 'https://mal-redesign.vercel.app',
    glink: 'https://github.com/SarcAceTic/mal-redesign',
    image: '/MALRedesign.png'
  },
  {
    name: 'VNDB Redesign',
    description:
      "This is my attempt on another UI redesign... since I couldn't stand the original website! It went pretty badly though... and I just stopped working on it. Though, I learned to use icons and to design better headers and UI in general!",
    link: null,
    glink: 'https://github.com/SarcAceTic/vndb-redesign',
    image: '/VNDB-Redesign.png'
  },
  {
    name: "Strawb's Portfolio",
    description:
      'This is a portfolio website project that I made for my artist friend. I REALLY liked how this turned out, and I also kind of experimented with some animations here and there. Turned out pretty decent, minus... the awkward animations though!',
    link: 'https://strawberrychae.vercel.app',
    glink: 'https://github.com/SarcAceTic/strawb-portfolio',
    image: '/StrawbPortfolio.png'
  }
]
</script>

<template>
  <v-container fluid>
    <section>
      <h2 class="mb-4 text-center text-purple-accent-3">My Projects</h2>
      <p :class="{'lg-p-size': lg, 'xl-p-size': xl, 'xxl-p-size': xxl}" class="text-center text-size my-5 mx-sm-5 mx-md-15">
        These are all projects that I've made, or have been working on so far! Take a gander...
        <br />
        (Some Projects have no website links, sorry about that!)
      </p>
      <v-row no-gutters>
        <v-col class="mx-auto my-5" cols="12" lg="5" v-for="project in projects">
          <v-card class="h-100" variant="flat">
            <div class="bg-black">
              <div class="h-100 mx-5 d-flex flex-column justify-space-between the-name">
                <h2 class="mt-5">{{ project.name }}</h2>
                <p :class="{'a-p-size': mdAndDown, 'lg-p-size': lg, 'xl-p-size': xl, 'xxl-p-size': xxl}">{{ project.description }}</p>
                <div class="mb-3">
                  <v-btn
                    :href="project.link"
                    target="_blank"
                    class="mr-4"
                    v-if="project.link"
                    variant="outlined"
                    color="purple-accent-1">
                    <v-icon class="mr-2">mdi-earth</v-icon>
                    Website Preview
                  </v-btn>
                  <v-btn :href="project.glink" target="_blank">
                    <v-icon class="mr-2">mdi-github</v-icon>
                    Github Repository
                  </v-btn>
                </div>
              </div>
              <v-img class="project-image" :src="project.image"></v-img>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </section>
  </v-container>
</template>

<style scoped>
.bg-black .project-image {
  opacity: 1;
  transition: opacity 0.3s;
}
.bg-black .the-name {
  opacity: 0;
  transition: opacity 0.3s;
}
.bg-black:hover .project-image {
  opacity: 0.2;
  transition: opacity 0.3s;
}
.bg-black:hover .the-name {
  opacity: 1;
  transition: opacity 0.3s;
}
.the-name {
  position: absolute;
  z-index: 1;
}
.the-name h3 {
  font-size: 20px;
}
</style>
