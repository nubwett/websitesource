<template>
    <v-container>
      <h2 class="headline font-weight-bold mb-3 text-center" id = "projects">Projects</h2>

      <v-layout
        mb-5
        py-5
        xs12 
        pt-5
        justify-center
        mx-auto
        row
        wrap
        md5
      >
        <v-flex md1>
            <v-img
            src = "../assets/dubhacks.png"
            width = "120"
            height = "50"
            ></v-img>
            <h3>@UW</h3>
        </v-flex>
        <v-flex md4 pl-5>
              <h2>Detox (October 2019)</h2>
          <p>
            Created a Google Chrome Extension that limits/prevents cyberbullying by
            censoring "toxic phrases/words." We created the Chrome Extension
            using Vue.js and used Google's API for sentiment analysis to analyze
            and determine what words are considered toxic or not. 
            <br>
            Team members: Kent Zeng, Allen Su, and Frank Hou.
          </p> 
            check out the github -->
            <v-btn text href = "https://github.com/nubwett/Detox"
              target="_blank" title = "GitHub pages">
                <v-icon>mdi-github-face</v-icon>
            </v-btn>
        </v-flex>
      </v-layout>


      
      <v-layout
        xs12 
        pt-5
        justify-center
        mx-auto
        row
        wrap
        md5>
        <v-flex md1>
            <v-img
              src = "../assets/codeday.png"
              width = "120"
          ></v-img>
          <h3>@Arizona</h3>
        </v-flex>
        <v-flex md4 pl-5>
            <h2>Agenda (February 2019)</h2>
          <p>
            Created an agenda maker that helps remind the use of what to do. Customize
            how you want to identify your events with tags and descriptions.
            Website was built with Javascript.
            <br>
            Team members: Ben Bousquet, James Jass.
          </p> 
            check out the website --> 
            <v-btn text href = "https://agenda-modern.surge.sh/"
              target="_blank" title = "GitHub pages">
                <v-icon>mdi-application</v-icon>
            </v-btn>
            <br>
            check out the github -->
            <v-btn text href = "https://github.com/nubwett/ytrack"
              target="_blank" title = "GitHub pages">
                <v-icon>mdi-github-face</v-icon>
            </v-btn>
        </v-flex>
      </v-layout>

      <v-layout
        xs12 
        pt-5
        justify-center
        mx-auto
        row
        wrap
        md5>
        <v-flex md1>
          <h1 class = "display-2 font-weight-bold mb-3">
        </h1>
      </v-flex>
        <v-flex md4 pl-5>
            <h2>yTrack (November 2018)</h2>
          <p>
            Created a number tracker that keeps track of each individual's score in a game.
            A lobby is created and can be joined by other individuals when given the key.
            Used Vue.js for the website design and Google's FireBase to update the scoreboard 
            real-time.
            <br>
            Team member: Ben Bousquet.
          </p> 
            check out the website --> 
            <v-btn text href = "https://ytrack-c3c34.firebaseapp.com/"
              target="_blank" title = "GitHub pages">
                <v-icon>mdi-application</v-icon>
            </v-btn>
            <br>
            check out the github -->
            <v-btn text href = "https://github.com/nubwett/ytrack"
              target="_blank" title = "GitHub pages">
                <v-icon>mdi-github-face</v-icon>
            </v-btn>
        </v-flex>
      </v-layout>

      <v-layout
        mb-5
        py-5
        xs12 
        pt-5
        justify-center
        mx-auto
        row
        wrap
        md5>
        <v-flex md1>
          <h1 class = "display-2 font-weight-bold mb-3">
        </h1>
      </v-flex>
          <v-flex md4 pl-5>
          <h2>Schooltools (February 2018)</h2>
          <p>
            Created a website with many tools to help aid with school subjects, 
            along with a ChemTools, which was created in a previous CodeDay that
            calculated the molar mass of a given molecule.

            <br>
            Team members: Ben Bousquet, James Jass.
          </p> 
          check out the website --> 
          <v-btn text href = "https://schooltools.surge.sh/"
            target="_blank" title = "GitHub pages">
              <v-icon>mdi-application</v-icon>
          </v-btn>
          <br>
          check out the github -->
          <v-btn text href = "https://github.com/nubwett/schooltools"
            target="_blank" title = "GitHub pages">
              <v-icon>mdi-github-face</v-icon>
          </v-btn>
        </v-flex>
      </v-layout>
  </v-container>
</template>