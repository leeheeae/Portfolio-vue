<template>
  <header class="header">
    <div class="logo">
      <img src="@/assets/images/hand.svg" alt="" /> LEEHEEAE
    </div>
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
  padding: 3rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: fixed;
  top: 0;
  left: 0;
}

.header .logo {
  display: flex;
  align-items: center;
  font-size: 1.5rem;
  font-weight: 900;
  user-select: none;
}
.header .logo img {
  width: 2.1rem;
  margin-right: 8px;
}
.header .logo:hover img {
  transform-origin: bottom;
  animation: rotateAni 0.8s forwards infinite;
}

@keyframes rotateAni {
  0% {
    transform: rotate(0deg);
  }
  50% {
    transform: rotate(20deg);
  }
  100% {
    transform: rotate(0deg);
  }
}

.header .menu-btn {
  cursor: pointer;
}
</style>