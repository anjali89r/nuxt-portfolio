<template>
  <v-container fluid class="footer">
    <v-row justify="center" align="center" class="pa-12 white--text">
       <v-col cols="12" class="text-center">

           <p> Website designed and coded by Anjali using Vue.js + Nuxt.
</p>

       <div>
          <v-btn href="https://www.linkedin.com/in/anjali-radhakrishnan-588512159/" text icon color="#fff">
              <v-icon>mdi-linkedin-box</v-icon>
            </v-btn>
            <v-btn href="https://github.com/anjali89r" text icon color="#fff">
              <v-icon>mdi-github-box</v-icon>
            </v-btn>
            <v-btn href="mailto:anjeng1989@gmail.com" text icon color="#fff">
              <v-icon>mdi-email</v-icon>
            </v-btn>
       </div>
       </v-col>

    </v-row>


  </v-container>
</template>
<script>
// import CookieLaw from 'vue-cookie-law'
export default {
  components: {
    // CookieLaw
  }
}
</script>

<style scoped>
.footer {
  background-color: #cb5b57;
}
.footer > .container,
.footer > .container-fluid {
  /* padding-top: 75px; */
  padding-bottom: 15px;
}
.footer hr {
  margin: 27px 0 21px;
  border-top-color: #3e3e3e;
}

.footer a {
  color: #fff !important;
  text-decoration: none;
}

.footer a:hover,
.footer a:focus {
  color: #fff;
}


</style>
