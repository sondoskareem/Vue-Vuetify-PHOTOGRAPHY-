<template>
  <v-app>


    <v-app-bar  flat color="white">
      <Header />
    </v-app-bar>


    <router-view></router-view>

    <Footer />

  </v-app>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",

  components: {
    Header,
    Footer,
  },
};
</script>
