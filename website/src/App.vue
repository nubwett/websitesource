<template>
  <v-app>

    <v-app-bar
      app
      color="blue"
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
        <span class="mr-2">home</span>
      </v-btn>

      <v-btn
        href="#about"
        text
      >        
        <span class="mr-2">about</span>
      </v-btn>
      
      <v-btn
        href="#projects"
        text
      >        
        <span class="mr-2">projects</span>
      </v-btn>
      <v-btn
        href="#RSOs"
        text
      >        
        <span class="mr-2">RSOs</span>
      </v-btn>

    </v-app-bar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
