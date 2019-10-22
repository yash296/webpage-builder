<template>
  <v-layout row wrap justify-center fill-height align-center>
    <v-flex xs12 class="text-center display-1">Select Landing Page To Proceed</v-flex>
    <v-flex xs12 sm6 pa-2>
      <v-card style="height:40vh">
        <v-btn block color="primary" nuxt to="/ladingPageTemplate">Continue</v-btn>
      </v-card>
    </v-flex>
    <v-flex xs12 sm6 pa-2>
      <v-card style="height:40vh">
        <v-btn block color="primary" nuxt to="/ladingPageTemplate">Continue</v-btn>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  components: {}
};
</script>
