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
<v-row justify="center" align="center" class="mb-9">
   <v-avatar
            class="profile"
            color="grey"
            size="164"
          >

              <v-img :src="profile.pic"></v-img>
          </v-avatar>
</v-row>
  </v-container>
  <v-parallax
    dark
    style="background-color:#cb5b57"
    src=""
    class="mb-9"
    :height="$vuetify.breakpoint.smAndDown ? '872' : '500'"
  >
    <v-row
      align="center"
      justify="center"
    >
      <v-col class="text-center" cols="7">
        <h1 class="display-1 font-weight-medium mb-4">Hi, I'm Anjali. Nice to meet you.</h1>
        <h4 class="font-weight-thin intro">I'm a self-taught programmer and an Udacity graduate from FrontEnd web development
Nanodegree program. Since beginning my journey as a freelance developer nearly two years ago, I have done internships, remote works for non-profit organization and startups. I'm quietly confident, naturally curious, and perpetually working on improving my skills.</h4>
    <h3 class="mt-4"> Currently open to new projects and other collaborations.</h3>
      </v-col>
    </v-row>
  </v-parallax>

<v-container>
  <v-row id="portfolio">
    <v-col cols="12" md="12" lg="9">
      <h2 class="display-1 font-weight-medium mb-8">Portfolio</h2>
       <v-timeline dense>
         <v-timeline-item
        color="#8D2C27"
        icon="computer"
      >

        <v-card class="elevation-0">
          <v-card-title class="text-uppercase" style="color:#8D2C27">Experience</v-card-title>

        </v-card>
      </v-timeline-item>

       <v-timeline-item
        color="#cb5b57"
        small
      >

        <v-card class="elevation-2">
          <v-card-title>Freelance Web Developer - <a class="demo-link" href="https://ekatvacollections.com" target="_blank"> Ekatva (https://ekatvacollections.com)</a></v-card-title>
           <v-card-subtitle color="#555555"> Present</v-card-subtitle>
           <v-card-text class="font-weight-medium">

           <ul>
             <li>Re-designed website for a retail client in Nuxt.js</li>
             <li>Work with designers to review the design mock and also demo after the implementation</li>
             <li>Developed additional routes as per the requirements</li>
           </ul>
          </v-card-text>
          <v-divider class="mx-4"></v-divider>
          <v-card-subtitle color="#555555">TECHNOLOGIES</v-card-subtitle>
          <v-card-text>

             <v-chip class="white--text" color="#cb5b57">Nuxt.js</v-chip>
        <v-chip class="white--text" color="#cb5b57">Vue.js</v-chip>

        <v-chip class="white--text" color="#cb5b57">Vuetify.js</v-chip>



      </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="#CB5B57"
        small
      >

        <v-card class="elevation-2">
          <v-card-title > Front-End Engineer - QOMPLX:</v-card-title>
          <v-card-subtitle color="#555555">June'19 - Oct'19</v-card-subtitle>
          <v-card-text class="font-weight-medium">

           <ul>
             <li>Designed and developed user-centric experiences using the latest web technologies</li>
             <li>Work with designers to review the design mock and also demo after the implementation</li>
             <li>Built additional custom JavaScript libraries or library extensions when required</li>
             <li>Worked on upgrading the Vuetify 1.5 version to use Vuetify 2.0</li>
             <li>Ensure technical feasibility of UI/UX designs</li>
             <li>Assure that all user input is valid before submitting to back-end</li>
             <li>Worked collaboratively to ensure consistent and performant approaches for the entire user experience</li>
           </ul>
          </v-card-text>
          <v-divider class="mx-4"></v-divider>
          <v-card-subtitle color="#555555">TECHNOLOGIES</v-card-subtitle>
          <v-card-text>

  <v-chip class="white--text" color="#cb5b57">Vue.js</v-chip>

        <v-chip class="white--text" color="#cb5b57">Vuetify.js</v-chip>

        <v-chip class="white--text" color="#cb5b57">JavaScript</v-chip>

        <v-chip class="white--text" color="#cb5b57">Bitbucket</v-chip>
        <v-chip class="white--text" color="#cb5b57">Jira</v-chip>



      </v-card-text>

        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="#CB5B57"
        small
      >

        <v-card class="elevation-2">
          <v-card-title > Freelance Web Developer</v-card-title>
          <v-card-subtitle color="#555555">Feb'19 - May'19</v-card-subtitle>
          <v-card-text class="font-weight-medium">
            Worked as a freelance web developer for multiple clients through Upwork and other remote opportunities. I have worked for 3 clients through Upwork to develop their website.
          </v-card-text>
          <v-divider class="mx-4"></v-divider>
          <v-card-subtitle color="#555555">TECHNOLOGIES</v-card-subtitle>
          <v-card-text>
        <v-chip class="white--text" color="#cb5b57">Vue.js</v-chip>
        <v-chip class="white--text" color="#cb5b57">Nuxt.js</v-chip>
        <v-chip class="white--text" color="#cb5b57">Vuetify.js</v-chip>
        <v-chip class="white--text" color="#cb5b57">JavaScript</v-chip>
        <v-chip class="white--text" color="#cb5b57">Github</v-chip>
      </v-card-text>
        </v-card>
      </v-timeline-item>

       <v-timeline-item
        color="#CB5B57"
        small
      >

        <v-card class="elevation-2">
          <v-card-title > Web Developer Intern - Ritekit</v-card-title>
          <v-card-subtitle color="#555555">Aug'18 - Jan'19</v-card-subtitle>
          <v-card-text class="font-weight-medium">

           <ul>
             <li>Rewrite the existing RiteKit.com website which was developed in PHP to Vue.js</li>
             <li>Create mock for Settings Page and review with Tech Lead </li>
             <li>Develop the pages in VueJs and bootstrap-vue </li>
             <li>Integrate the existing apis and verify the data is displayed properly</li>
             <li>Review the code with Tech Lead </li>
             <li>Track the tasks in Asana and groom the story with Tech Lead</li>
           </ul>
          </v-card-text>
          <v-divider class="mx-4"></v-divider>
          <v-card-subtitle color="#555555">TECHNOLOGIES</v-card-subtitle>
          <v-card-text>
        <v-chip class="white--text" color="#cb5b57">Vue.js</v-chip>

        <v-chip class="white--text" color="#cb5b57">Bootstrap-Vue</v-chip>

        <v-chip class="white--text" color="#cb5b57">JavaScript</v-chip>

        <v-chip class="white--text" color="#cb5b57">Bitbucket</v-chip>
        <v-chip class="white--text" color="#cb5b57">Asana</v-chip>

      </v-card-text>

        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="#CB5B57"
        small
      >

        <v-card class="elevation-2">
          <v-card-title > Web Designer - PTI(non-profit services)</v-card-title>
          <v-card-subtitle color="#555555">Feb'18 - April'18</v-card-subtitle>
          <v-card-text class="font-weight-medium">

           <ul>
             <li>Worked as independent contractor creating responsive websites in WordPress for non- profit communities.</li>
             <li>Understand requirements from the clients, create design docs, mockups and attend review calls with the clients to walkthrough the mockups. </li>
           </ul>
          </v-card-text>
          <v-divider class="mx-4"></v-divider>
          <v-card-subtitle color="#555555">TECHNOLOGIES</v-card-subtitle>
          <v-card-text>

        <v-chip class="white--text" color="#cb5b57">WordPress</v-chip>

        <v-chip class="white--text" color="#cb5b57">JavaScript</v-chip>

      </v-card-text>

        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="#CB5B57"
        small
      >

        <v-card class="elevation-2">
          <v-card-title > Software Engineer Intern - ProjectOne</v-card-title>
          <v-card-subtitle color="#555555">Dec'17 - Jan'18</v-card-subtitle>
          <v-card-text class="font-weight-medium">

           <ul>
             <li>Supported the frontend development to enhance their web application using jQuery, React.js</li>

           </ul>
          </v-card-text>
          <v-divider class="mx-4"></v-divider>
          <v-card-subtitle color="#555555">TECHNOLOGIES</v-card-subtitle>
          <v-card-text>

        <v-chip class="white--text" color="#cb5b57">React.js</v-chip>
  <v-chip class="white--text" color="#cb5b57">JavaScript</v-chip>
        <v-chip class="white--text" color="#cb5b57">Github</v-chip>

      </v-card-text>

        </v-card>
      </v-timeline-item>

       <v-timeline-item
        color="#cb5b57"
        small
      >

        <v-card class="elevation-2">
          <v-card-title > Freelance Web-Developer - Medinovita </v-card-title>
          <v-card-subtitle color="#555555">June'17 - Nov'17</v-card-subtitle>
          <v-card-text class="font-weight-medium">

           <ul>
             <li>Developed responsive user interfaces</li>
             <li>Integrate api with the web pages using AJAX</li>
             <li>Defect fixes for the issues raised by QA team</li>

           </ul>
          </v-card-text>
          <v-divider class="mx-4"></v-divider>
          <v-card-subtitle color="#555555">TECHNOLOGIES</v-card-subtitle>
          <v-card-text>

        <v-chip class="white--text" color="#cb5b57">jQuery</v-chip>
  <v-chip class="white--text" color="#cb5b57">Bootstrap</v-chip>
        <v-chip class="white--text" color="#cb5b57">Github</v-chip>

      </v-card-text>

        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="#CB5B57"
        small
      >

        <v-card class="elevation-2">
          <v-card-title > Red Cross Volunteer</v-card-title>
          <v-card-subtitle color="#555555">Mar’16-Mar’17</v-card-subtitle>
          <v-card-text class="font-weight-medium">

           <ul>
             <li>Managed the planning and development of the training courses for the field volunteers in Chesapeake Area (DE & MD states)</li>
             <li>Compiled and validated the training data to create new reports weekly or biweekly to share to the Red Cross Director -Delmarva Chapter</li>
           </ul>
          </v-card-text>


        </v-card>
      </v-timeline-item>
        <v-timeline-item
        color="#8D2C27"
        icon="star"
      >

        <v-card class="elevation-0">
          <v-card-title class="text-uppercase" style="color:#8D2C27">Certification</v-card-title>

        </v-card>
      </v-timeline-item>

<v-timeline-item
        color="#CB5B57"
        small
      >

        <v-card class="elevation-2">
         <v-card-text class="font-weight-medium">

           <ul>
             <li>Front-End Developer Nanodegree graduate from Udacity(2018)</li>
             <li>Recipient of Grow with Google Developer Scholarship to the Front-End Web Developer Nanodegree program – 2018</li>
           </ul>
          </v-card-text>
        </v-card>
      </v-timeline-item>


        <v-timeline-item
        color="#8D2C27"
        icon="school"
      >

        <v-card class="elevation-0">
          <v-card-title class="text-uppercase" style="color:#8D2C27">Education</v-card-title>

        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="#CB5B57"
        small
      >

        <v-card class="elevation-2">
         <v-card-text class="font-weight-medium">

           <ul>
             <li>Masters in Control & Instrumentation Engineering
Anna University, India</li>
             <li>Bachelor in Applied Electronics & Instrumentation
Engineering, India</li>
           </ul>
          </v-card-text>
        </v-card>
      </v-timeline-item>
    </v-timeline>
    </v-col>
  </v-row>
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
  <v-fab-transition>
                <v-btn

                  color="#cb5b57"
                  fab
                  dark
                  absolute
                  bottom
                  right
                  @click="top"
                >
                  <v-icon>mdi-arrow-up</v-icon>
                </v-btn>
              </v-fab-transition>
</v-container>
  </div>
</template>

<script>

export default {
  data: () => ({
      profile: {
        pic: require('../assets/profile.jpeg')
      },
      items: [
        {
          title: 'Classic Arcade Game Clone',
          text: "An HTML5 Canvas powered video game, developed using the best practices in Object Oriented JavaScript. The goal of the player is to reach the water, without colliding into any one of the enemies.",
          subtext: 'Newly released songs. Updated daily.',
          img: 'https://images.unsplash.com/photo-1498038432885-c6f3f1b912ee?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2100&q=80',
          test: {
            sample: require('../assets/game.png')
          },
          link: 'https://anjali89r.github.io/frontend-nanodegree-arcade-game/'
        },
        {
          title: 'Memory Game',
          text: 'Built a complete browser-based card matching game (also known as Concentration). But this isn’t just any memory game! it’s a shnazzy, well-designed, feature-packed memory game!',
          link: 'https://anjali89r.github.io/fend-project-memory-game/',
           test: {
            sample: require('../assets/memory.png')
          }
        },
        {
          title: 'A Book Lending App',
          text: 'A responsive web application that allows users to select and categorize books into a virtual bookshelf. Leveraged React to support a dynamic user interface that interacts with an API server and client library.',
          link: 'https://github.com/anjali89r/react-my-reads',
           test: {
            sample: require('../assets/readingApp.png')
          }
        },
      ],
      transparent: 'rgba(255, 255, 255, 0)',
    }),
   methods:{
      top(){
             window.scrollTo({
  top: 0,
  left: 0,
  behavior: 'smooth'
});
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
