<template>
  <v-app>
    <v-app-bar app color="white" dark>
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
      </div>-->

      <v-spacer></v-spacer>

      <v-btn @click="$vuetify.goTo('#home')" text>
        <span class="mr-2 black--text">home</span>
      </v-btn>

      <v-btn @click="$vuetify.goTo('#about')" text>
        <span class="mr-2 black--text">about</span>
      </v-btn>

      <v-btn @click="$vuetify.goTo('#projects')" text>
        <span class="mr-2 black--text">projects</span>
      </v-btn>
      <v-btn @click="$vuetify.goTo('#RSOs')" text>
        <span class="mr-2 black--text">RSOs</span>
      </v-btn>
    </v-app-bar>

    <v-content>
      <Intro style="background: #FFAF7B" id="home" />
      <About id="about" style="background: #FFFEE0" />
      <Projects style="background: #B4E3F5" id="projects" />
      <RSOs id="RSOs" style="background: #FFAF7B" />
      <Hobbies style="background: #FFFEC8" />
      <Copyright style= "background: grey"/>
    </v-content>
  </v-app>
</template>

<script>
import Intro from "./components/Intro";
import About from "./components/About";
import Projects from "./components/Projects";
import RSOs from "./components/RSOs";
import Hobbies from "./components/Hobbies";
import Copyright from "./components/Copyright";

export default {
  name: "App",

  components: {
    Intro,
    About,
    Projects,
    RSOs,
    Hobbies,
    Copyright
  },

  created () {
    document.title = "Evan Hao";
  },
  data: () => ({
    //
  })
};

</script>
