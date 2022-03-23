<template>
  <section class="about-container">
    <div class="container">
      <div class="text-box">
        <h2 class="main-text Averta">
          A passionate developer<br />
          who wants to run together
        </h2>
        <p class="sub-text">
          UX/UX 디자이너로 웹 제작을 처음 시작했으며, 그 경험을 화면에 보여지는
          부분에 대한 작업에 대한 자신감이 있습니다.<br />
          디자인과 개발 간의 흐름을 이해하고 디자이너, 개발자와의 원활한 소통이
          가능합니다.<br />
          다양한 경험을 통해 생기게 되는 문제를 해결하기 위해 꾸준히 고민하고
          노력합니다.
        </p>
        <ul class="tag-list">
          <li>이희애</li>
          <li>1996.11.26</li>
          <li>부산</li>
          <li>frontend developer</li>
          <li>UI/UX Designer</li>
        </ul>
      </div>
      <div class="img-box">
        <div></div>
        <div></div>
        <div></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.main-text {
  font-size: 2rem;
  font-weight: 600;
  line-height: 1.4;
  color: var(--main-text-color);
}
.text-box .sub-text {
  font-size: 0.9rem;
  line-height: 2;
  color: var(--gray-color-02);
  margin: 2.6rem 0 4rem;
}
.text-box .tag-list {
  display: flex;
  flex-wrap: wrap;
}
.text-box .tag-list li {
  font-size: 0.84rem;
  margin: 0 0.6rem 1rem 0;
  padding: 0.7rem 1.2rem;
  border-radius: 2rem;
  color: var(--white-color);
  background-color: var(--gray-color-01);
}
.img-box {
  margin-top: 5rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: flex-start;
}
.img-box div {
  width: 100%;
  height: 200px;
  margin-bottom: 5%;
  border-radius: 8px;
  background: #ddd;
}

/* media */
@media (min-width: 350px) {
  .main-text {
    font-size: 1.8rem;
  }
}

@media (min-width: 460px) {
  .main-text {
    font-size: 2rem;
  }
  .img-box div {
    height: 260px;
  }
}

@media (min-width: 768px) {
  .main-text {
    font-size: 2.4rem;
  }

  .text-box .sub-text {
    font-size: 0.94rem;
  }

  .text-box .tag-list li {
    font-size: 0.9rem;
  }
}

@media (min-width: 1024px) {
  .img-box div {
    width: 31%;
    height: 260px;
  }
}

@media (min-width: 1200px) {
  .main-text {
    font-size: 2.6rem;
  }
  .sub-text {
    font-size: 1.1rem;
  }
}
@media (min-width: 1400px) {
  .main-text {
    font-size: 3rem;
  }
  .img-box div {
    width: 31%;
    height: 280px;
  }
}
</style>