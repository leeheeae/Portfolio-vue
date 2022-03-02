<template>
  <HeaderVue />
  <RouterView />
</template>

<script>
import HeaderVue from "@/components/common/Header.vue";

export default {
  components: {
    HeaderVue,
  },
};
</script>

<style>
@import url("@/assets/reset.css");
@import url("@/assets/base.css");
</style>