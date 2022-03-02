<template>
  <section>
    <div class="container">
      <SectionTitleVue title01="About" title02="me" />
      <div class="contents">
        <div class="img-box">
          <img src="@/assets/images/about_me2.png" alt="img" />
        </div>
        <div class="info-box">
          <div class="profile">
            <h2 class="name">이희애 <span>(Lee heeae)</span></h2>
            <p>1996. 11. 26</p>
            <p>+82 10 2332 5270</p>
            <p>chromeee@daum.net</p>
          </div>

          <div class="comment">
            <h2>디자인하는 프론트앤드 개발자</h2>
            <p>
              UX/UX 디자이너로 웹 제작을 처음 시작했으며, 그 경험을 통해 화면에
              보이는 부분들을 쉽게 배우고 이해합니다. 디자인과 개발 간의 흐름을
              이해하고 작업이 진행되기 때문에 디자이너, 개발자와의 원활한 소통이
              가능합니다. 다양한 경험을 통해 생기게 되는 문제를 해결하기 위해
              꾸준히 고민하고 노력합니다
            </p>
          </div>
        </div>
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
.contents {
  margin-top: 3rem;
  display: flex;
}
.contents .img-box {
  max-width: 800px;
  height: 600px;
  width: 60%;
}
.contents .info-box {
  width: 40%;
}

.contents .info-box .profile {
  background: #dadada;
  padding: 2.2rem;
  border-radius: 1.5rem;
}

.contents .info-box .profile .name {
  font-size: 1.2rem;
  font-weight: 600;
}

.contents .info-box .profile p {
  margin-top: 10px;
}

.contents .info-box .comment {
  margin-top: 3rem;
}

.contents .info-box .comment h2 {
  font-size: 1.6rem;
  font-weight: 600;
}

.contents .info-box .comment p {
  margin-top: 1rem;
  font-size: 1rem;
  line-height: 1.8;
}
</style>