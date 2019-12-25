<template>
  <v-container py-10>
    <h1 class="display-2 font-weight-bold text-center">Evan Hao</h1>
    <v-container py-10>
      <v-layout row wrap justify-center xs12>
        <v-flex xs12 md4>
          <v-card raised>
            <v-card-title>A Website About Me</v-card-title>
            <v-card-text class="text--primary body-1">
              <p>Freshman at the University of Washington</p>
              <p>Currently in Engineering Undeclared</p>
              <p>Intended Computer Engineering Major</p>
              <v-btn text icon class = "mr-5" href="./resume.pdf" target="_blank" title="Resume">
                <v-icon>mdi-file-account</v-icon>
                <p>resume</p>
              </v-btn>
              <v-btn text icon class = "mr-5" href="https://github.com/nubwett" target="_blank" title="GitHub">
                <v-icon>mdi-github-box</v-icon>
                <p>GitHub</p>
              </v-btn>
              <v-btn
                text
                icon
                href="https://www.linkedin.com/in/evanhao/"
                target="_blank"
                title="LinkedIn"
                class = "mr-5"
              >
                <v-icon>mdi-linkedin</v-icon>
                <p>Linkedin</p>
              </v-btn>
            </v-card-text>
          </v-card>
        </v-flex>

        <v-flex xs12 md3>
          <v-img src="../assets/pfp.jpg" contain height="300"></v-img>
        </v-flex>
      </v-layout>
    </v-container>
  </v-container>
</template>