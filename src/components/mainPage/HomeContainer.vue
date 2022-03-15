<template>
  <section class="home-container">
    <div class="container">
      <h1 class="main-text Averta">
        A passionate developer <br />who wants to run together
      </h1>
      <p class="sub-text">
        함께 달리고 싶은 열정적 프론트앤드 개발자 이희애입니다.
      </p>
      <div class="btn-list">
        <button class="talk-btn Averta">Let's Talk</button>
        <button class="project-btn Averta">Project View</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.home-container {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  min-height: 100vh;
  padding: 10rem 2.4rem;
}
.main-text {
  font-size: 1.6rem;
  line-height: 1.5;
  color: var(--main-text-color);
}
.sub-text {
  font-size: 0.9rem;
  line-height: 2;
  color: var(--gray-color-02);
  margin: 20px 0 60px;
}
.btn-list {
  display: flex;
  align-items: center;
}
.btn-list button {
  width: 150px;
  padding: 1rem 0;
  text-align: center;
  font-size: 0.9rem;
  border-radius: 5px;
  transition: var(--transition);
}
.btn-list .talk-btn {
  background-color: var(--gray-color-01);
  color: var(--main-text-color);
  margin-right: 10px;
}
.btn-list .talk-btn:hover {
  background-color: var(--white-color);
  color: var(--black-color);
}
.btn-list .project-btn {
  border: 1px solid var(--gray-color-02);
  color: var(--white-color);
}

@media (min-width: 350px) {
  .main-text {
    font-size: 1.8rem;
  }
}

@media (min-width: 460px) {
  .main-text {
    text-align: center;
    font-size: 2.2rem;
  }
  .sub-text {
    text-align: center;
  }
  .btn-list {
    justify-content: center;
  }
}

@media (min-width: 768px) {
  .main-text {
    font-size: 2.6rem;
  }
  .btn-list {
    font-size: 1rem;
  }
}

@media (min-width: 1200px) {
  .main-text {
    font-size: 3.2rem;
  }
  .sub-text {
    font-size: 1.1rem;
  }
  .btn-list button {
    width: 210px;
    padding: 1.2rem 0;
  }
}
@media (min-width: 1400px) {
  .main-text {
    font-size: 3.8rem;
  }
  .btn-list {
    font-size: 1.1rem;
  }
}
</style>