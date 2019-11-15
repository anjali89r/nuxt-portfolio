<template>
<div>
<v-container>
  <v-row justify="center" align="center" class="mt-9 mb-5">
    <h1 class="display-2 text-center">
      Front-end VueJS Developer
    </h1>
  </v-row>
  <v-row justify="center" align="center" class="mb-9">
    <v-subheader class="title">With every line of code, I strive to make the web a beautiful place.</v-subheader>
  </v-row>

  </v-container>

<v-container>
  <v-row class="mt-9 mb-8" id="projects">
    <v-col cols="12">
      <h2 class="display-1 font-weight-medium mt-6">Personal Projects</h2>
       <v-row class="fill-height" align="center" justify="center">
      <template v-for="(item, i) in items">
        <v-col
          :key="i"
          cols="12"
          md="4"
        >
          <v-hover v-slot:default="{ hover }">
            <v-card

            class="project"
              :elevation="hover ? 12 : 2"
              :class="{ 'on-hover': hover }"
              :href="item.link"
            >
               <v-img
        :aspect-ratio="16/9"
        :src="item.test.sample"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-3 v-card--reveal display-3 white--text"
            style="height: 100%;"
          >
            Demo
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-title class="base--text"> {{item.title}}</v-card-title>

          <v-card-text class="font-weight-medium">
            {{item.text}}
          </v-card-text>

            </v-card>
          </v-hover>
        </v-col>
      </template>
    </v-row>
    </v-col>
  </v-row>
</v-container>
  </div>
</template>

<script>

export default {
  data: () => ({
      profile: {
        pic: require('../../assets/profile.jpeg')
      },
      items: [
        {
          title: 'Classic Arcade Game Clone',
          text: "An HTML5 Canvas powered video game, developed using the best practices in Object Oriented JavaScript. The goal of the player is to reach the water, without colliding into any one of the enemies.",
          subtext: 'Newly released songs. Updated daily.',
          img: 'https://images.unsplash.com/photo-1498038432885-c6f3f1b912ee?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2100&q=80',
          test: {
            sample: require('../../assets/game.png')
          },
          link: 'https://anjali89r.github.io/frontend-nanodegree-arcade-game/'
        },
        {
          title: 'Memory Game',
          text: 'Built a complete browser-based card matching game (also known as Concentration). But this isn’t just any memory game! it’s a shnazzy, well-designed, feature-packed memory game!',
          link: 'https://anjali89r.github.io/fend-project-memory-game/',
           test: {
            sample: require('../../assets/memory.png')
          }
        },
        {
          title: 'A Book Lending App',
          text: 'A responsive web application that allows users to select and categorize books into a virtual bookshelf. Leveraged React to support a dynamic user interface that interacts with an API server and client library.',
          link: 'https://github.com/anjali89r/react-my-reads',
           test: {
            sample: require('../../assets/readingApp.png')
          }
        },
      ],
      transparent: 'rgba(255, 255, 255, 0)',
    }),
    methods: {
      demo(link) {
        this.$router.push(link)
      }
    }
}
</script>
<style scoped>
.intro {
  letter-spacing: 1px;
  line-height: 1.765rem;
}
.theme--light.v-card > .v-card__text, .theme--light.v-card .v-card__subtitle {
  color: #555555;
}
.v-card__text {
  font-size: 1rem;
}
.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: .5;
  position: absolute;
  width: 100%;
}
.v-card.project:hover {
  cursor: pointer;
}
</style>
