<template>
  <div>
    <NavBar />
    <Hero v-bind:user="user" />
    <Footer />
  </div>
</template>

<script>
import NavBar from "@/components/navbar";
import Footer from "@/components/footer";
import Hero from "@/components/hero";
export default {
  name: "Index",
  components: { NavBar, Footer, Hero },
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
