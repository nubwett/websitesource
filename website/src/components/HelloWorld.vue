<template>
  <v-container>
      <v-container         style = "background: #3A1C71;
    background: -webkit-linear-gradient(to right, #FFAF7B, #D76D77, #3A1C71);
    background: linear-gradient(to right, #FFAF7B, #D76D77, #3A1C71);">
        <v-layout 
          row 
          wrap
          justify-center
        >
          <v-flex xs12 md4 px-10 pt-10>
            <h1 class="display-2 font-weight-bold mb-3">
              Evan Hao
            </h1>
            <p>Freshman at the University of Washington</p>
            <p>Intended Computer Engineering Major</p>

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

    <v-layout
      text-center
      wrap
      mx-10
    >
      <v-flex
        mb-5
        xs12
        md8
        mx-auto
        py-5
        justify-center
      >
        <h2 class="headline font-weight-bold mb-3" id = "projects">Projects</h2>
        
        <v-layout justify-center>
          <a
            v-for="(next, i) in whatsNext"
            :key="i"
            :href="next.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ next.text }}
          </a>
        </v-layout>
      </v-flex>

      <v-flex
        xs12
        mb-5
      >
        <h2 class="headline font-weight-bold mb-3">Important Links</h2>

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

      <v-flex
        xs12
        mb-5
      >
        <h2 class="headline font-weight-bold mb-3">Coding Hobbies</h2>

        <v-layout justify-center>
          <a
            v-for="(eco, i) in coding"
            :key="i"
            :href="eco.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ eco.text }}
          </a>
        </v-layout>
      </v-flex>
    </v-layout>
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
    importantLinks: [
      {
        text: 'Documentation',
        href: 'https://vuetifyjs.com',
      },
      {
        text: 'Chat',
        href: 'https://community.vuetifyjs.com',
      },
      {
        text: 'Made with Vuetify',
        href: 'https://madewithvuejs.com/vuetify',
      },
      {
        text: 'Twitter',
        href: 'https://twitter.com/vuetifyjs',
      },
      {
        text: 'Articles',
        href: 'https://medium.com/vuetify',
      },
    ],
    whatsNext: [
      {
        text: 'Explore components',
        href: 'https://vuetifyjs.com/components/api-explorer',
      },
      {
        text: 'Select a layout',
        href: 'https://vuetifyjs.com/layout/pre-defined',
      },
      {
        text: 'Frequently Asked Questions',
        href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
      },
    ],
  }),
};
</script>
