<template>
  <HeaderVue />
  <router-view></router-view>
</template>

<script>
import HeaderVue from "./components/common/Header.vue";

export default {
  components: {
    HeaderVue,
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