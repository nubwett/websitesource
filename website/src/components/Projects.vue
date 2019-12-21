<template>
  <v-container flex py-10>
    <v-container>
      <h2 class="headline font-weight-bold mb-3 text-center" id="projects">Projects</h2>

      <v-layout py-5 xs12 pt-5 justify-center mx-auto row wrap md5>
        <v-flex md1>
          <v-img src="../assets/dubhacks.png" width="120" height="50"></v-img>
          <h3>@UW</h3>
        </v-flex>
        <v-flex md4 pl-5>
          <h2>Detox (October 2019)</h2>
          <p>
            Created a Google Chrome Extension that limits/prevents cyberbullying by
            censoring "toxic phrases/words." We created the Chrome Extension
            using Vue.js and used Google's API for sentiment analysis to analyze
            and determine what words are considered toxic or not.
            <br />Team members: Kent Zeng, Allen Su, and Frank Hou.
          </p>
          <v-btn text href="https://github.com/nubwett/Detox" target="_blank" title="GitHub pages">
            <v-icon>mdi-github-circle</v-icon>
          </v-btn>
        </v-flex>
      </v-layout>

      <v-layout py-5 xs12 pt-5 justify-center mx-auto row wrap md5>
        <v-flex md1>
          <v-img src="../assets/apcapstone.png" width="120"></v-img>
          <h3>@Basis Scottsdale</h3>
        </v-flex>
        <v-flex md4 pl-5>
          <h2>AP Research (April 2019)</h2>
          <p>
            Analyzed Korean-pop (K-pop) music and the effects globalization had on its culture.
            Through the drastic differences in communication styles of Korea and the West, my research
            shows the emphasis on more of Korea's culture rather than complete Westernization of K-pop.
            <br />Research Mentor: Dr. Sunyoung Yang at University of Arizona.
            <br />Resarch Advisor: Lyndsay Haag.
          </p>
          <v-btn
            text
            href="https://evanapresearch.wordpress.com/"
            target="_blank"
            title="Blog Website"
          >
            <v-icon>mdi-post</v-icon>
          </v-btn>
          <v-btn
            text
            href="https://docs.google.com/document/d/1N6qIECRvNwZmVGTwdAR1YhA4zrLniTa82AeroxPf-1U/edit?usp=sharing"
            target="_blank"
            title="Research Paper"
          >
            <v-icon>mdi-file-outline</v-icon>
          </v-btn>
          <v-btn
            text
            href="https://docs.google.com/presentation/d/1IMNtVQTZ9A5zpidEgXxkAZMOWrFuwcTVs67wSsJQmJ4/edit?usp=sharing"
            target="_blank"
            title="Presentation"
          >
            <v-icon>mdi-presentation</v-icon>
          </v-btn>
        </v-flex>
      </v-layout>

      <v-layout xs12 pt-5 justify-center mx-auto row wrap md5>
        <v-flex md1>
          <v-img src="../assets/liml.png" width="120" height></v-img>
          <h3>@Arizona</h3>
        </v-flex>
        <v-flex md4 pl-5>
          <h2>LIML (April 2018 - February 2019)</h2>
          <p>
            Created a website to assist high school students with AP Computer Science A and
            AP Calculus. The website provides generated AP Calculus questions along with lessions
            and practice exam solutions to AP Computer Science questions.
            <br />Team member: Suhas Vittal.
          </p>
          <v-btn text href="http://liml.us-east-2.elasticbeanstalk.com/" target="_blank" title="LIML">
            <v-icon>mdi-web</v-icon>
          </v-btn>
        </v-flex>
      </v-layout>

      <v-layout xs12 pt-5 justify-center mx-auto row wrap md5>
        <v-flex md1>
          <v-img src="../assets/codeday.png" width="120" height></v-img>
          <h3>@Arizona</h3>
        </v-flex>
        <v-flex md4 pl-5>
          <h2>Agenda (February 2019)</h2>
          <p>
            Created an agenda maker that helps remind the use of what to do. Customize
            how you want to identify your events with tags and descriptions.
            Website was built with Javascript.
            <br />Team members: Ben Bousquet, James Jass.
          </p>
          <v-btn text href="https://agenda-modern.surge.sh/" target="_blank" title="Agenda">
            <v-icon>mdi-web</v-icon>
          </v-btn>
          <v-btn text href="https://github.com/nubwett/agenda" target="_blank" title="GitHub">
            <v-icon>mdi-github-circle</v-icon>
          </v-btn>
        </v-flex>
      </v-layout>

      <v-layout xs12 pt-5 justify-center mx-auto row wrap md5>
        <v-flex md1>
          <h1 class="display-2 font-weight-bold mb-3"></h1>
        </v-flex>
        <v-flex md4 pl-5>
          <h2>yTrack (November 2018)</h2>
          <p>
            Created a number tracker that keeps track of each individual's score in a game.
            A lobby is created and can be joined by other individuals when given the key.
            Used Vue.js for the website design and Google's FireBase to update the scoreboard
            real-time.
            <br />Team member: Ben Bousquet.
          </p>
          <v-btn text href="https://ytrack-c3c34.firebaseapp.com/" target="_blank" title="yTrack">
            <v-icon>mdi-web</v-icon>
          </v-btn>
          <v-btn text href="https://github.com/nubwett/ytrack" target="_blank" title="GitHub">
            <v-icon>mdi-github-circle</v-icon>
          </v-btn>
        </v-flex>
      </v-layout>

      <v-layout mb-5 py-5 xs12 pt-5 justify-center mx-auto row wrap md5>
        <v-flex md1>
          <h1 class="display-2 font-weight-bold mb-3"></h1>
        </v-flex>
        <v-flex md4 pl-5>
          <h2>Schooltools (February 2018)</h2>
          <p>
            Created a website with many tools to help aid with school subjects,
            along with a ChemTools, which was created in a previous CodeDay that
            calculated the molar mass of a given molecule.
            <br />Team members: Ben Bousquet, James Jass.
          </p>
          <v-btn text href="https://schooltools.surge.sh/" target="_blank" title="School Tools">
            <v-icon>mdi-web</v-icon>
          </v-btn>
          <v-btn text href="https://github.com/nubwett/schooltools" target="_blank" title="GitHub">
            <v-icon>mdi-github-circle</v-icon>
          </v-btn>
        </v-flex>
      </v-layout>
    </v-container>
  </v-container>
</template>