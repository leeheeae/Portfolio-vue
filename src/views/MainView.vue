<template>
  <main>
    <NaviVue />
    <MainVue />
    <AboutVue />
    <Experience />
    <Portfolio />
    <Contact />
    <Footer />
  </main>
</template>

<script>
import NaviVue from "@/components/common/Navi.vue";
import MainVue from "@/components/main/main/Main.vue";
import AboutVue from "@/components/main/about/About.vue";
import Experience from "@/components/main/experience/Experience.vue";
import Portfolio from "@/components/main/portfolio/Portfolio.vue";
import Contact from "@/components/main/contact/Contact.vue";
import Footer from "@/components/main/footer/Footer.vue";

export default {
  components: {
    NaviVue,
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