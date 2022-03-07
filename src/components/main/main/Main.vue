<template>
  <section class="main-section" id="home">
    <WaveItem />
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

<script>
import WaveItem from "@/components/svg/WaveItem.vue";
export default { components: { WaveItem } };
</script>

<style scoped>
.main-section {
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
  margin-bottom: 1rem;
  text-align: center;
}

.text-main-contents h1 {
  font-size: 3.6rem;
  font-weight: 900;
  color: var(--text-main-color);
  line-height: 1.4;
  text-align: center;
}

.text-main-contents h1 span {
  color: var(--black-color);
}

.text-main-contents .talk-btn {
  display: block;
  margin: 3.2rem auto 0;
  text-align: center;
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

.text-main-contents .talk-btn:active {
  transform: var(--btn-active);
}
</style>