<template>
  <v-app>

    <v-app-bar
      app
      color="white"
      dark
    >
      <!-- <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />
        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
      </div> -->

      <v-spacer></v-spacer>

      <v-btn
        href="#"
        text
      >        
        <span class="mr-2 black--text ">home</span>
      </v-btn>

      <v-btn
        href="#about"
        text
      >        
        <span class="mr-2 black--text ">about</span>
      </v-btn>
      
      <v-btn
        href="#projects"
        text
      >        
        <span class="mr-2 black--text ">projects</span>
      </v-btn>
      <v-btn
        href="#RSOs"
        text
      >        
        <span class="mr-2 black--text ">RSOs</span>
      </v-btn>

    </v-app-bar>

    <v-content>
      <Intro/>
      <About id = "about"/>
      <Projects/>
      <RSOs/>
      <Hobbies/>
    </v-content>
  </v-app>
</template>

<script>
import Intro from './components/Intro';
import About from './components/About';
import Projects from './components/Projects';
import RSOs from './components/RSOs';
import Hobbies from './components/Hobbies';

export default {
  name: 'App',

  components: {
    Intro, About, Projects, RSOs, Hobbies
  },

  data: () => ({
    //
  }),
};
</script>
