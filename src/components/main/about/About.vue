<template>
  <section>
    <div class="container">
      <div class="info-contents">
        <ul>
          <li>
            <h3>이름</h3>
            <p>이희애</p>
          </li>
          <li>
            <h3>생년월일</h3>
            <p>1996.11.26</p>
          </li>
          <li>
            <h3>연락처</h3>
            <p>010-2332-5270</p>
          </li>
          <li>
            <h3>이메일</h3>
            <p>chromeee@daum.net</p>
          </li>
        </ul>
      </div>
      <div class="intro-contents">
        <h2>
          디자인하는<br />
          프론트앤드 개발자
        </h2>
        <p>
          UX/UX 디자이너로 웹 제작을 처음으로 접했으며 웹에서 제공되는 모든
          정보들을 다양한 방법으로 표현해나가는 것에 재미를 느낍니다. 그 경험을
          통해 화면에 보이는 부분들을 쉽게 배우고 이해합니다. 디자인과 개발 간의
          흐름을 이해하고 작업이 진행되기 때문에 디자이너, 개발자와의 원활한
          소통이 가능합니다. 다양한 경험을 통해 생기게 되는 문제를 해결하기 위해
          꾸준히 고민하고 노력합니다
        </p>
      </div>
    </div>
  </section>
</template>

<script>
import SectionTitleVue from "@/components/common/SectionTitle.vue";

export default {
  components: {
    SectionTitleVue,
  },
};
</script>

<style scoped>
.info-contents {
  background: #f5f7fb;
  border-radius: 1rem;
  padding: 2rem 2.5rem;
}

.info-contents ul {
  display: flex;
  justify-content: space-between;
}

.info-contents li h3 {
  font-size: 0.9rem;
  color: #555;
  margin-bottom: 10px;
}

.info-contents li p {
  font-size: 1.2rem;
  font-weight: 600;
}

.intro-contents {
  margin-top: 3rem;
  display: flex;
  line-height: 1.4;
}
.intro-contents h2 {
  white-space: nowrap;
  font-size: 2rem;
  margin-right: 6rem;
}
</style> 