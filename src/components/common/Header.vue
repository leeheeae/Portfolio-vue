<template>
  <header class="header">
    <div class="logo Averta">
      <router-link to="/"> LEEHEEAE <span>🖐🏻</span> </router-link>
    </div>
    <button class="menu-btn">메뉴</button>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
.header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  padding: 2rem 1.6rem;
  display: flex;
  justify-content: space-between;
}

.header .logo {
  font-size: 1.3rem;
}
</style>