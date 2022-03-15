<template>
  <HomeContainerVue />
  <AboutContainerVue />
  <ScrollIconVue />
  <SkillContainerVue />
</template>

<script>
import ScrollIconVue from "../components/common/ScrollIcon.vue";
import HomeContainerVue from "../components/mainPage/HomeContainer.vue";
import AboutContainerVue from "../components/mainPage/AboutContainer.vue";
import SkillContainerVue from "../components/mainPage/SkillContainer.vue";

export default {
  components: {
    ScrollIconVue,
    HomeContainerVue,
    AboutContainerVue,
    SkillContainerVue,
  },
};
</script>

<style>
</style>