<template>
  <section class="main-section" id="home">
    <div class="container">
      <div class="text-main-contents">
        <h4>WEB FRONTEND DEVELOPER</h4>
        <h1>
          함께 달리고 싶은<br />열정적인 개발자 <span>이희애</span>입니다.
        </h1>
        <button class="talk-btn">바로 연락하기</button>
      </div>
    </div>
  </section>
</template>

<style scoped>
.main-section {
  min-height: 100vh;
  display: flex;
  /* justify-content: center; */
  align-items: center;
}

.waveItem {
  position: fixed;
  top: 0;
  left: 0;
  transform: translate(-40%, -30%);
  z-index: -1;
}

.text-main-contents h4 {
  font-size: 1.2rem;
  font-weight: 400;
  color: var(--gray-color);
  margin-bottom: 10px;
}

.text-main-contents h1 {
  font-size: 4.4rem;
  font-weight: 700;
  line-height: 1.4;
}

.text-main-contents .talk-btn {
  display: block;
  margin-top: 4rem;
  text-align: center;
  padding: 1.2rem 4rem;
  border-radius: 3rem;
  font-size: 1.1rem;
  font-weight: 500;
  color: white;
  background: var(--main-color);
  transition: var(--transition);
}

.text-main-contents .talk-btn:hover {
  background: var(--main-color-hover);
}

.text-main-contents .talk-btn:active {
  transform: var(--btn-active);
}
</style>