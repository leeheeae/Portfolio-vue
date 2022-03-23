<template>
  <div class="main-page">
    <bgItemVue :itemTop="'0%'" :itemLeft="'5vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'12%'" :itemLeft="'80vw'" :itemOpacity="0.2" />
    <bgItemVue :itemTop="'18%'" :itemLeft="'10vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'35%'" :itemLeft="'70vw'" :itemOpacity="0.2" />
    <bgItemVue :itemTop="'48%'" :itemLeft="'-8vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'60%'" :itemLeft="'60vw'" :itemOpacity="0.2" />
    <bgItemVue :itemTop="'72%'" :itemLeft="'20vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'80%'" :itemLeft="'100vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'92%'" :itemLeft="'15vw'" :itemOpacity="0.3" />
    <HomeContainerVue />
    <AboutContainerVue />
    <ScrollIconVue />
    <SkillContainerVue />
    <ProjectContainerVue />
    <FooterVue />
  </div>
</template>

<script>
import ScrollIconVue from "../components/common/ScrollIcon.vue";
import HomeContainerVue from "../components/mainPage/HomeContainer.vue";
import AboutContainerVue from "../components/mainPage/AboutContainer.vue";
import SkillContainerVue from "../components/mainPage/SkillContainer.vue";
import ProjectContainerVue from "../components/mainPage/ProjectContainer.vue";
import FooterVue from "../components/common/Footer.vue";
import bgItemVue from "../components/bgItem.vue";

export default {
  components: {
    ScrollIconVue,
    HomeContainerVue,
    AboutContainerVue,
    SkillContainerVue,
    ProjectContainerVue,
    FooterVue,
    bgItemVue,
  },
};
</script>

<style scoped>
.main-page {
  position: relative;
  width: 100%;
  height: 100%;
  overflow: hidden;
}
</style>