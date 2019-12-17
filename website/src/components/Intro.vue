<template>
  <v-container py-10>
        <h1 class="display-2 font-weight-bold text-center">Evan Hao</h1>
    <v-container py-10>
      <v-layout row wrap justify-center>
        <v-flex xs12 md3 px-10 pt-10>
          <p>Freshman at the University of Washington</p>
          <p>
            Currently in Computer Engineering
            <br />Intended Computer Engineering Major
          </p>

          <v-btn text icon href="assets/.pdf" target="_blank" title="Resume">
            <v-icon>mdi-file-account</v-icon>
          </v-btn>

          <v-btn text icon href="https://github.com/nubwett" target="_blank" title="GitHub">
            <v-icon>mdi-github-box</v-icon>
          </v-btn>

          <v-btn
            text
            icon
            href="https://www.linkedin.com/in/evanhao/"
            target="_blank"
            title="LinkedIn"
          >
            <v-icon>mdi-linkedin</v-icon>
          </v-btn>
        </v-flex>

        <v-flex xs12 md2>
          <v-img src="../assets/pfp.jpg" contain height="300"></v-img>
        </v-flex>
      </v-layout>
    </v-container>
  </v-container>
</template>