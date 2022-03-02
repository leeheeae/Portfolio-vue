<template>
  <header class="header">
    <div class="logo">LEEHEEAE</div>
    <div class="menu-btn"><IconMenuVue /></div>
  </header>
</template>

<script>
import IconMenuVue from "../icons/IconMenu.vue";

export default {
  components: {
    IconMenuVue,
  },
};
</script>

<style scoped>
.header {
  width: 100%;                      
  padding: 1rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: fixed;
  top: 0;
  left: 0;
}

.header .logo {
  font-size: 1.4rem;
  font-weight: 500;
}

.header .menu-btn {
  cursor: pointer;
}
</style>