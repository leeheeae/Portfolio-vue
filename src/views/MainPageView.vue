<template>
  <HomeContainerVue />
  <AboutContainerVue />
  <ScrollIconVue />
  <SkillContainerVue />
  <ProjectContainerVue />
</template>

<script>
import ScrollIconVue from "../components/common/ScrollIcon.vue";
import HomeContainerVue from "../components/mainPage/HomeContainer.vue";
import AboutContainerVue from "../components/mainPage/AboutContainer.vue";
import SkillContainerVue from "../components/mainPage/SkillContainer.vue";
import ProjectContainerVue from "../components/mainPage/ProjectContainer.vue";

export default {
  components: {
    ScrollIconVue,
    HomeContainerVue,
    AboutContainerVue,
    SkillContainerVue,
    ProjectContainerVue,
  },
};
</script>

<style>
</style>