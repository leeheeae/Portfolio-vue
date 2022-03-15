<template>
  <HeaderVue />
  <router-view></router-view>
  <FooterVue />
</template>

<script>
import HeaderVue from "./components/common/Header.vue";
import FooterVue from "./components/common/Footer.vue";

export default {
  components: {
    HeaderVue,
    FooterVue,
  },
};
</script>

<style>
@import url("@/assets/reset.css");
@import url("@/assets/base.css");

body {
  background-color: var(--main-bg-color);
}
</style>