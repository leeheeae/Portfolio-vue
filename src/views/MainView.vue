<template>
  <div>
    <MainVue />
    <AboutVue />
    <Experience />
    <Portfolio />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import MainVue from "@/components/main/main/Main.vue";
import AboutVue from "@/components/main/about/About.vue";
import Experience from "@/components/main/experience/Experience.vue";
import Portfolio from "@/components/main/portfolio/Portfolio.vue";
import Contact from "@/components/main/contact/Contact.vue";
import Footer from "@/components/main/footer/Footer.vue";

export default {
  components: {
    MainVue,
    AboutVue,
    Experience,
    Portfolio,
    Contact,
    Footer,
  },
};
</script>

<style>
</style>