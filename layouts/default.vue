<template>
  <v-app>
    <NavBar />
    <v-content>
      <nuxt />
    </v-content>
    <Footer />
  </v-app>
</template>
<script>
import NavBar from '@/components/NavBar'
import Footer from '@/components/Footer'

export default {
  components: {
    NavBar,
    Footer
  },
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Portfolio'
    }
  }
}
</script>
<style>
.theme--light.v-application {
  /* background: #f6f6f4; */
  background: #fff;
  color: #555555;
}
.v-application, .v-application .display-1, .v-application .display-2, .v-application .title {
  font-family: 'Fira Sans', sans-serif !important;
}

.v-application a {
  color: #555555 !important;
  /* color: #000; */
  text-decoration: none;
}

.card-pointer:hover {
  cursor: pointer;
}
.base--text {
  color: #cb5b57;
}
</style>
