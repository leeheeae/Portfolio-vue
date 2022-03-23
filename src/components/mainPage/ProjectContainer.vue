<template>
  <section class="project-container">
    <div class="container">
      <div class="text-box">
        <h2 class="main-text Averta">featured Projects 🥗</h2>
        <p class="sub-text">
          UI/UX 디자이너로 일했을 때의 프로젝트부터 개발공부를 통한
          Toy프로젝트등을 확인할 수 있습니다.
        </p>
      </div>

      <ul class="project-list">
        <li>
          <div class="info-box">
            <h4 class="info-title Averta">Toy Project</h4>
            <h2 class="project-title">나의 기억 저장소</h2>
          </div>
        </li>
        <li>
          <div class="info-box">
            <h4 class="info-title Averta">Toy Project</h4>
            <h2 class="project-title">나의 기억 저장소</h2>
          </div>
        </li>
        <li>
          <div class="info-box">
            <h4 class="info-title Averta">Toy Project</h4>
            <h2 class="project-title">나의 기억 저장소</h2>
          </div>
        </li>
        <li>
          <div class="info-box">
            <h4 class="info-title Averta">Toy Project</h4>
            <h2 class="project-title">나의 기억 저장소</h2>
          </div>
        </li>
      </ul>

      <router-link to="" class="more-btn">
        <button>Project More</button>
      </router-link>
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
.sub-text {
  font-size: 0.9rem;
  line-height: 2;
  color: var(--gray-color-02);
  margin: 0.6rem 0 3rem;
}

.project-list {
  display: flex;
  flex-wrap: wrap;
}
.project-list > li {
  position: relative;
  width: 100%;
  border-radius: 1.4rem;
  height: 320px;
  margin-bottom: 1rem;
  background-color: rgba(255, 255, 255, 0.1);
}
.project-list > li .info-box {
  position: absolute;
  left: 1.2rem;
  bottom: 1.2rem;
  max-width: 340px;
  padding: 1rem 3rem 1rem 1.2rem;
  border-radius: 1rem;
  background: rgba(255, 255, 255, 0.2);
  opacity: 0;
  transform: translateY(10px);
  transition: 0.3s;
}
.project-list > li:hover .info-box {
  opacity: 1;
  transform: translateY(0);
}
.project-list > li .info-box .info-title {
  margin-bottom: 2px;
  font-size: 0.86rem;
  color: var(--point-color);
  line-height: 1.5;
}
.project-list > li .info-box .project-title {
  font-size: 1.1rem;
  font-weight: 400;
  line-height: 1.5;
  color: var(--main-text-color);
}
.more-btn {
  display: block;
  width: 200px;
  margin: 2rem auto;
  padding: 1rem 1.4rem;
  text-align: center;
  border-radius: 0.5rem;
  font-size: 1rem;
  font-weight: 600;
  background: var(--gray-color-01);
}
.more-btn button {
  color: var(--white-color);
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
}

@media (min-width: 768px) {
  .main-text {
    font-size: 2.2rem;
  }

  .text-box .sub-text {
    font-size: 0.94rem;
  }

  .text-box .tag-list li {
    font-size: 0.9rem;
  }
}

@media (min-width: 1024px) {
  .project-list {
    justify-content: space-between;
  }
  .project-list > li {
    position: relative;
    width: 49%;
    height: 340px;
    margin-bottom: 2%;
  }
}

@media (min-width: 1200px) {
  .main-text {
    font-size: 2.4rem;
  }
  .sub-text {
    font-size: 1.1rem;
  }
}
@media (min-width: 1400px) {
  .main-text {
    font-size: 2.8rem;
  }
  .project-list > li {
    height: 360px;
  }
}
</style>