<template>
  <div>
    <NavBar />
    <Hero v-bind:user="user" />
    <Tickers />
    <Footer />
  </div>
</template>

<script>
import NavBar from "@/components/navbar";
import Footer from "@/components/footer";
import Hero from "@/components/hero";
import Tickers from "@/components/tickers";
export default {
  name: "Index",
  components: { NavBar, Footer, Hero, Tickers },
  data() {
    return {
      user: this.getUserMachine(),
    };
  },
  methods: {
    getUserMachine() {
      return window.navigator.appVersion;
    },
  },
};
</script>

<style></style>
