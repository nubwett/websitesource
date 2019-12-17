<template>
  <v-container>
      <v-container>
      <h1 class = "display-2 font-weight-bold text-center">Evan Hao</h1>
        <v-layout 
          row 
          wrap
          justify-center
        >
          <v-flex xs12 md3 px-10 pt-10>
            <p>Freshman at the University of Washington</p>
            <p>Currently in Computer Engineering <br> Intended Computer Engineering Major</p>

              <v-btn text icon href = "assets/.pdf"
              target="_blank" title = "Resume">
                <v-icon>mdi-file-account</v-icon>
              </v-btn>

              <v-btn text icon href = "https://github.com/nubwett" 
              target="_blank" title = "GitHub">
                <v-icon>mdi-github-box</v-icon>
              </v-btn>

              <v-btn 
              text icon href = "https://www.linkedin.com/in/evanhao/" 
              target="_blank" title = "LinkedIn"
              >
                <v-icon>mdi-linkedin</v-icon>
              </v-btn>
          </v-flex>

          <v-flex xs12 md2 py-10>
            <v-img
              src = "../assets/pfp.jpg"
              contain
              height="300"
            ></v-img>
          </v-flex>
      </v-layout>
      </v-container>


    <v-container>
      <v-flex xd12 md8>
        <h1 class = "display-2 font-weight-bold mb-3">
        </h1>
      </v-flex>
    </v-container>

    
  <v-container>
    <v-flex
        mb-5
        xs12
        md5
        mx-auto
        py-5
        justify-center
      >
        <h2 class="headline font-weight-bold mb-3 text-center" id = "about">About</h2>
        <p> Hello! My name is Evan Hao.</p>
        <p>
          I am currently a Freshman studying at the University of Washington (UW). 
          I entered UW as Engineering Undeclared in hopes to become a Computer Engineer.
          
          "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."


        </p>
        <v-layout justify-center>
        </v-layout>
      </v-flex>
  </v-container>

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
      
  <v-container>
      <v-flex
        xs12
        mb-5
      >
        <h2 class="headline font-weight-bold mb-3 text-center " id = "RSOs">Registered Student Organizations</h2>
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
            src = "../assets/DFA.png"
            width = "120"
            contain
            ></v-img>
            <h3>@UW</h3>
        </v-flex>
        <v-flex md4 pl-5>
              <h2>Design for America (September 2019 - Present)</h2>
          <p>
            Tackling the current issue of "Freshman 15" where we examine the factors for why many 
            Freshman are synonymous with having an unhealthy lifestyle when they enter college.
            <br>
            Team members: Jeffrey Qiu (Lead), Andrew Tang, Jennifer Konishi, Lily Liu, and Melody Yeung
          </p> 
            check out our presentation slides -->
            <v-btn text href = "https://drive.google.com/open?id=1CGSEMf0jIYn41XRCUdg_Pnp0kDVS28AcFpe837eJ34k"
              target="_blank" title = "Presentation">
                <v-icon>mdi-presentation</v-icon>
            </v-btn>
        </v-flex>
      </v-layout>
        <v-layout justify-center>
          <a
            v-for="(link, i) in importantLinks"
            :key="i"
            :href="link.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ link.text }}
          </a>
        </v-layout>
      </v-flex>
  </v-container>
  
    <v-container>
        <v-flex
          xs12
          mb-5
        >
          <h2 class="headline font-weight-bold mb-3 text-center">Hobbies / Random Things</h2>
          <p class = "text-center">Evolution of my username: Noob --> Newb --> Newblett --> Nublett --> <b>Nubwett</b> </p>

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
              text-center
            >
          
            <v-flex md3 mx-5>
            <v-card>
              <v-card-title class = "justify-center">Games I Play</v-card-title>
              <v-card-text class = "text--primary body-1">
            <p>Counter-Strike:Global Offensive</p>
            <p>League of Legends</p>
            <p>Maplestory</p>
            <p>A Dance of Fire and Ice</p>
            <p>Muse Dash</p>
            <p>Osu</p>
              </v-card-text>
              </v-card>
          </v-flex>

            <v-flex md3 mx-5>
            <v-card>
              <v-card-title class = "justify-center">Misc. Extracurriculars</v-card-title>
              <v-card-text class = "text--primary body-1">
             <p>Asian-American Intervarsity</p>
            <p>Asian-American Christian Fellowship</p>
            <p>Camp Kesem UW</p>
            <p>Husky Swim Club</p>
            <p>Purple Caster Minions</p>
            <p>Gaming Association at UW</p>
            <p>Taiwanese Student Organization</p>
            <p>Chinese Student Organization</p>
            <p>Japanese Student Organization</p>
            <p>Korean Student Organization</p>
              </v-card-text>
              </v-card>
          </v-flex>

          <v-flex md3 mx-5>
            <v-card>
              <v-card-title class = "justify-center">Things I Love</v-card-title>
              <v-card-text class = "text--primary body-1">
              <p><a href = "https://open.spotify.com/user/22v7nvjatk6jsqp4dsm6zvkkq?si=5ClLogI5Q8SPShK5RO1lMw"
                target="_blank" title = "Spotify"> Spotify
              </a></p>
              <p>I love food</p>
              <p></p>
              <p>Origami</p> 
              <p>Table-Tennis</p>
              <p>Swimming</p>
              <p>Tennis</p>
              </v-card-text>
              </v-card>
          </v-flex>

          </v-layout>
        </v-flex>
    </v-container>
              <!-- <v-layout justify-center>
            <a
              v-for="(eco, i) in coding"
              :key="i"
              :href="eco.href"
              class="subheading mx-3"
              target="_blank"
            >
              {{ eco.text }}
            </a>
          </v-layout> -->
  </v-container>
</template>

<script>
export default {
  name: 'HelloWorld',

  data: () => ({
    coding: [
      {
        text: 'Project Euler',
        href: 'https://projecteuler.net/progress=nubwett',
      },
      {
        text: 'Leetcode',
        href: 'https://leetcode.com/nubwett/',
      },
      {
        text: 'awesome-vuetify',
        href: 'https://github.com/vuetifyjs/awesome-vuetify',
      },
    ],
  }),
};
</script>
