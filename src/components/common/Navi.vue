<template>
  <nav class="nav">
    <ul>
      <li class="active">
        <a href="#home"><span>Home</span></a>
      </li>
      <li>
        <a href="#about"><span>About</span></a>
      </li>
      <li>
        <a href="#skill"><span>Skill</span></a>
      </li>
      <li>
        <a href="#projects"><span>Projects</span></a>
      </li>
      <li>
        <a href="#contact"><span>Contact</span></a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.nav {
  position: fixed;
  top: 50%;
  right: 1rem;
  transform: translateY(-50%);
}

.nav ul {
  display: flex;
  flex-direction: column;
  gap: 0.7rem;
  text-align: right;
}

.nav li {
  font-size: 0.88rem;
  font-weight: 500;
}

.nav li a {
  display: flex;
  justify-content: right;
  align-items: center;
}

.nav li a::after {
  display: block;
  content: "";
  width: 1.4rem;
  margin-left: 6px;
  height: 2px;
  background: var(--gray-color);
}

.nav li span {
  color: var(--gray-color);
  opacity: 0;
}

.nav li.active span,
.nav li:hover span {
  color: var(--black-color);
  opacity: 1;
}
.nav li.active a::after,
.nav li a:hover::after {
  background: var(--black-color);
}
</style>