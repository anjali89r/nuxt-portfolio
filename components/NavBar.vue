<template>
  <div>
      <!-- <v-navigation-drawer
         v-model="sideNav"
         absolute
         temporary
         right
         class="sideDrawer hidden-md-and-up"
         >

      <v-list
        dense
        nav
      >
        <v-list-item
          link
        >
          <v-list-item-icon>
            <v-icon></v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>
               <router-link to='/portfolio'>Portfolio</router-link>
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
         <v-list-item
          link
        >
          <v-list-item-icon>
            <v-icon></v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>
               <router-link to='/projects'>Projects</router-link>
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer> -->
    <v-container>
      <v-row justify="center" align="center">
        <v-app-bar  color="elevation-0">

          <v-toolbar-title to="/">
            <v-avatar color="#CB5B57" size="48">
              <!-- <img
                src="https://cdn.vuetifyjs.com/images/john.jpg"
                alt="John"
              />  -->
              <a href="/"><span class="white--text headline">AR</span></a>
              </v-avatar>
          </v-toolbar-title>

          <v-spacer></v-spacer>
          <!-- <v-app-bar-nav-icon @click.native.stop="sideNav=!sideNav" class="hidden-md-and-up"></v-app-bar-nav-icon> class="hidden-sm-and-down"-->
<div >
          <v-btn :large="btnSize"   href="/portfolio" text class="text-capitalize"
            ><span class="custom-line">Portfolio</span></v-btn
          >
          <v-btn :large="btnSize"  to="/projects"  text class="text-capitalize"
            ><span class="custom-line">Projects</span></v-btn
          >
</div>

        </v-app-bar>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {
   data() {
      return {
         sideNav: null
      }
   },
   computed: {
     btnSize() {
       return this.$vuetify.breakpoint.mdAndUp ? true : false;
     }
   }
}
</script>
<style scoped>
.v-btn.v-size--large {
  font-size: 1rem;
}

span.custom-line {
  position: relative;
}

span.custom-line::before {
  content: '';
  position: absolute;
  margin-bottom: -3px;
  left: 50%;
  bottom: 0;
  width: 100%;
  height: 2px;
  background-color: #CB5B57;
  transform-origin: center;
  transform: translate(-50%, 0) scaleX(0);
  transition: transform 0.3s ease-in-out;
}

span.custom-line:hover::before {
  transform: translate(-50%, 0) scaleX(1);
}
</style>
