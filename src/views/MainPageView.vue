<template>
  <div class="main-page">
    <bgItemVue :itemTop="'0%'" :itemLeft="'5vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'12%'" :itemLeft="'80vw'" :itemOpacity="0.2" />
    <bgItemVue :itemTop="'20%'" :itemLeft="'10vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'35%'" :itemLeft="'70vw'" :itemOpacity="0.2" />
    <bgItemVue :itemTop="'48%'" :itemLeft="'-8vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'60%'" :itemLeft="'60vw'" :itemOpacity="0.2" />
    <bgItemVue :itemTop="'72%'" :itemLeft="'10vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'80%'" :itemLeft="'100vw'" :itemOpacity="0.3" />
    <bgItemVue :itemTop="'89%'" :itemLeft="'80vw'" :itemOpacity="0.1" />
    <bgItemVue :itemTop="'94%'" :itemLeft="'15vw'" :itemOpacity="0.2" />
    <HomeContainerVue />
    <AboutContainerVue />
    <SkillContainerVue />
    <ProjectContainerVue />
    <ScrollIconVue />
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
section {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  padding: 10rem 2rem;
}

/* media */
@media (min-width: 460px) {
  section {
    padding: 10rem 2.5rem;
  }
}

@media (min-width: 768px) {
  section {
    padding: 10rem 3rem;
  }
}

@media (min-width: 1024px) {
  section {
    padding: 10rem 3.5rem;
  }
}

@media (min-width: 1200px) {
  section {
    padding: 10rem 4rem;
  }
}
</style>