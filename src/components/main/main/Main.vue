<template>
  <section class="main-section">
    <div class="container">
      <div class="text-main-contents">
        <h4>WEB FRONTEND DEVELOPER</h4>
        <h1>
          함께 달리고 싶은<br />열정적인 개발자 <span>이희애</span>입니다.
        </h1>
        <button class="talk-btn">Let's Talk</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.main-section {
  display: flex;
  /* justify-content: center; */
  align-items: center;
}

.text-main-contents h4 {
  font-size: 1.2rem;
  font-weight: 400;
  color: var(--gray-color);
  margin-bottom: 1rem;
}

.text-main-contents h1 {
  font-size: 3.6rem;
  font-weight: 900;
  color: var(--text-main-color);
  line-height: 1.3;
}

.text-main-contents h1 span {
  color: var(--black-color);
}

.text-main-contents .talk-btn {
  margin-top: 3.2rem;
  text-align: center;
  align-items: 84px;
  padding: 1.2rem 4rem;
  border-radius: 3rem;
  font-size: 1.2rem;
  font-weight: 600;
  color: white;
  background: var(--main-color);
  transition: var(--transition);
}

.text-main-contents .talk-btn:hover {
  background: var(--main-color-hover);
}
</style>