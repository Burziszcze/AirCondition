<template>
    <v-footer height="auto" class="black">
    <v-layout row wrap justify-center>
      <v-flex xs12 sm6 py-3 text-xs-center white--text>
          Data comes from API <i class="fas fa-cloud"></i> <a href="http://aqicn.org/api/pl/"><strong>aqicn.org</strong></a></v-flex>
      <v-flex xs12 sm6 py-3 text-xs-center white--text>
          App made with <i id="heart-ico" class="fas fa-heart"></i>by <a data-v-40ab164b="" href="https://burziszcze.github.io/"><strong>Paweł Jarosz</strong></a> ©</v-flex>
    </v-layout>
  </v-footer>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      msg: "This is footer component"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
