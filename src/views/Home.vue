<template>
  <v-content class="pa-0 dcfont">
    <v-container fluid class="" style="background-color:#212121">
      <v-layout wrap align-center justify-center row fill-height class="">
        <v-flex xs12 md10 class="" my-5>
          <HomeStartScreen />
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid style="background-color:#303030">
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="" my-4>
          <whatWeDo />
        </v-flex>
      </v-layout>
    </v-container>

    <!-- Copied WhatWeDo section to build WhatWeOffer -->

    <v-container fluid style="background-color:#212121">
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="" my-4>
          <whatWeOffer />
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid style="background-color:#303030">
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="" my-3>
          <AboutPyGoa />
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid style="background-color:#212121">
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="" my-3>
          <AboutGDGChapter />
        </v-flex>
      </v-layout>
    </v-container>

    <!-- <v-container fluid style="background-color:#303030">
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <eventshowcase />
        </v-flex>
      </v-layout>
    </v-container> -->

    <!-- <v-container fluid class="py-5" style="background-color:#212121">
      <v-layout wrap align-start justify-start row fill-height>
        <v-flex xs12 md10 offset-md1 offset-lg1 >
          <p class="google-font mb-2" style="font-size:150%">Our Feature Event & Meetup</p>
        </v-flex>
        <v-flex xs12 md10 offset-md1 offset-lg1 >
          <featureEvent />
        </v-flex>
      </v-layout>
    </v-container> -->

    <!-- <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10>
          <wtmInfo />
        </v-flex>
      </v-layout>
    </v-container> -->

    <v-container fluid style="background-color:#303030">
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 my-3>
          <partners />
        </v-flex>
      </v-layout>
    </v-container>
  </v-content>
</template>

<script>
import HomeStartScreen from "@/components/home/HomeStartScreen";
import whatWeDo from "@/components/home/whatWeDo";
import whatWeOffer from "@/components/home/whatWeOffer";
import AboutPyGoa from "@/components/home/AboutPyGoa";
import AboutGDGChapter from "@/components/home/AboutGDGChapter";
// import eventshowcase from "@/components/home/eventshowcase";
// import wtmInfo from '@/components/home/wtmInfo'
import partners from "@/components/home/partners";
// import featureEvent from "@/components/home/featureEvent";

export default {
  components: {
    HomeStartScreen,
    whatWeDo,
    whatWeOffer,
    AboutPyGoa,
    AboutGDGChapter,
    // eventshowcase,
    // wtmInfo,
    partners,
    //featureEvent
  },
};
</script>

<style>
.dcfont {
  color: white;
}
</style>
