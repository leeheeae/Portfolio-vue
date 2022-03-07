<template>
  <section>
    <div class="container">
      <SectionTitleVue title01="Skill" title02="List" />
      <div class="contents">
        <div class="front">
          <div class="icon"></div>
          <h2>Frontend Tools</h2>
          <ul>
            <li class="main-force">HTML</li>
            <li class="main-force">CSS</li>
            <li class="main-force">Vanila JS</li>
            <li class="main-force">Vue JS</li>
            <li>React JS</li>
            <li>JQuery</li>
          </ul>
        </div>

        <div class="back">
          <div class="icon"></div>
          <h2>Backend Tools</h2>
          <ul>
            <li>Node JS (express)</li>
            <li>MySQL</li>
          </ul>
        </div>

        <div class="design">
          <div class="icon"></div>
          <h2>Design Tools</h2>
          <ul>
            <li>Adobe Photoshop</li>
            <li>Adobe illustrator</li>
            <li>Adobe XD</li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import SectionTitleVue from "../../common/SectionTitle.vue";
export default {
  components: {
    SectionTitleVue,
  },
};
</script>

<style scoped>
.contents {
  margin-top: 4rem;
}

.contents > div {
  margin: 5rem 0;
}
.contents h2 {
  font-size: 1.3rem;
  font-weight: 600;
  margin-bottom: 10px;
}
.contents ul {
  display: flex;
}
.contents li {
  padding: 1rem 1.5rem;
  border-radius: 0.8rem;
  box-shadow: 5px 10px 20px rgba(0, 0, 0, 0.1);
  background: #fff;
  margin-right: 0.8rem;
  font-size: 1rem;
  font-weight: 500;
}
.contents li.main-force {
  box-shadow: 5px 10px 20px rgba(255, 58, 118, 0.1);
  color: #ff3a76;
}
</style>