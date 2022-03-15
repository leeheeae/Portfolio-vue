<template>
  <section class="skill-container">
    <div class="container">
      <div class="text-box">
        <h2 class="main-text Averta">
          A passionate developer <br />who wants to run together 😎
        </h2>
        <p class="sub-text">
          프론트앤드 기술부터 디자인, 백엔드 기술까지 다양한 언어와 기술들을
          습득하고, 새로운 기술들을 배우는것에 두려워하지 않습니다.
        </p>
      </div>
      <ul class="tool-list">
        <!-- front -->
        <li>
          <h3 class="tool-title Averta">Frontend Tools 🚗</h3>
          <p class="comment">
            마크업 태그부터 HTTP 통신을 통한 데이터까지 다양한 툴을 이용하여
            작업이 가능합니다.
          </p>
          <ul class="skill-list">
            <li>HTML</li>
            <li>CSS</li>
            <li>JS</li>
            <li>VUEJS</li>
            <li>REACTJS</li>
            <li>Jqeury</li>
          </ul>
        </li>

        <!-- back -->
        <li>
          <h3 class="tool-title Averta">Backend Tools 🚓</h3>
          <p class="comment">
            마크업 태그부터 HTTP 통신을 통한 데이터까지 다양한 툴을 이용하여
            작업이 가능합니다.
          </p>
          <ul class="skill-list">
            <li>NODEJS</li>
            <li>MYSQL</li>
          </ul>
        </li>

        <!-- Design -->
        <li>
          <h3 class="tool-title Averta">Design Tools 🎁</h3>
          <p class="comment">
            어도비의 디자인 툴을 이용하여 사진을 편집하고 UI/UX에 관한 모든
            디자인을 작업합니다.
          </p>
          <ul class="skill-list">
            <li>Adobe Photoshop</li>
            <li>Adobe illustrator</li>
            <li>Adobe XD</li>
          </ul>
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.skill-container {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  padding: 10rem 2.4rem;
  background: rgba(255, 255, 255, 0.1);
}
.text-box .main-text {
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
.tool-list {
  display: flex;
  flex-direction: column;
}
.tool-list > li {
  padding: 1.8rem 2rem;
  background-color: rgba(255, 255, 255, 0.2);
  border-radius: 1.5rem;
  margin-bottom: 1rem;
}
.tool-list .tool-title {
  font-size: 1.2rem;
  color: var(--point-color);
  margin-bottom: 10px;
}
.tool-list .comment {
  font-size: 0.84rem;
  font-weight: 300;
  line-height: 1.7;
  color: var(--white-color);
}
.tool-list .skill-list {
  margin-top: 1.2rem;
  display: flex;
  flex-wrap: wrap;
}
.tool-list .skill-list > li {
  width: 3rem;
  height: 3rem;
  background: #eee;
  margin: 8px 8px 0 0;
  border-radius: 0.3rem;
  font-size: 0.6rem;
  text-align: center;
}
.tool-list .skill-list > li:last-child {
  margin-right: 0;
}
</style>
