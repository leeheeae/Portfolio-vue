<template>
  <HomeContainerVue />
  <AboutContainerVue />
  <ScrollIconVue />
</template>

<script>
import ScrollIconVue from "../components/common/ScrollIcon.vue";
import HomeContainerVue from "../components/mainPage/HomeContainer.vue";
import AboutContainerVue from "../components/mainPage/AboutContainer.vue";

export default {
  components: { ScrollIconVue, HomeContainerVue, AboutContainerVue },
};
</script>

<style>
</style>