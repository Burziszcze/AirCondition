<template>
  <v-app>
    <v-toolbar dark color="dark">
          <v-toolbar-title>
            AirCondition app
          </v-toolbar-title>
    </v-toolbar>
    <v-content>
      <HelloWorld/>
    </v-content>
    <Footer></Footer>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Content from "./components/Content";
import Footer from "./components/Footer";

export default {
  data() {
    return {
      clipped: false,
      drawer: true,
      fixed: false,
      items: [
        {
          icon: "bubble_chart",
          title: "Inspire"
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js"
    };
  },
  name: "App",
  components: {
    HelloWorld,
    Content,
    Footer,
  }
};
</script>
<style>
.fa-heart {
  color: #f44336;
}
.fa-cloud {
  color: #90caf9;
}
footer a:hover {
  color: #90caf9;
}

footer a {
  color: white;
  text-decoration: #90caf9;
}
</style>

