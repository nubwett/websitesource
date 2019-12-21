<template>
  <v-container white--text text-center>
    <v-flex xs12 mx-auto py-5 justify-center color = "white">
      <p>
        Designed and built by Evan Hao using Vue / Vuetify and hosted on GitHub Pages.
        <v-container xs12>
              <v-btn text icon class = "mx-5" href="assets/resume.pdf" target="_blank" title="Resume">
                <v-icon>mdi-file-account</v-icon>
              </v-btn>
              <v-btn text icon class = "mx-5" href="https://github.com/nubwett" target="_blank" title="GitHub">
                <v-icon>mdi-github-box</v-icon>
              </v-btn>
              <v-btn
                text
                icon
                href="https://www.linkedin.com/in/evanhao/"
                target="_blank"
                title="LinkedIn"
                class = "mx-5"
              >
                <v-icon>mdi-linkedin</v-icon>
              </v-btn>
        </v-container>

      </p>
      <v-layout justify-center></v-layout>
    </v-flex>
  </v-container>
</template>