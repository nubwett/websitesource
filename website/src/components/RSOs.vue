<template>
  <v-container py-10>
    <v-flex xs12 mb-5>
      <h2
        class="headline font-weight-bold mb-3 text-center"
        id="RSOs"
      >Registered Student Organizations</h2>
      <v-layout mb-5 py-5 xs12 pt-5 justify-center mx-auto row wrap md5>
        <v-flex md1>
          <v-img src="../assets/DFA.png" width="120" contain></v-img>
          <h3>@UW</h3>
        </v-flex>
        <v-flex md4 pl-5>
          <h2>Design for America (September 2019 - Present)</h2>
          <p>
            Tackling the current issue of "Freshman 15" where we examine the factors for why many
            Freshman are synonymous with having an unhealthy lifestyle when they enter college.
            <br />Team members: Jeffrey Qiu (Lead), Andrew Tang, Jennifer Konishi, Lily Liu, and Melody Yeung
          </p>check out our presentation slides -->
          <v-btn
            text
            href="https://drive.google.com/open?id=1CGSEMf0jIYn41XRCUdg_Pnp0kDVS28AcFpe837eJ34k"
            target="_blank"
            title="Presentation"
          >
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
        >{{ link.text }}</a>
      </v-layout>
    </v-flex>
  </v-container>
</template>