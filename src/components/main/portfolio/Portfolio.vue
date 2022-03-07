<template>
  <section>
    <div class="container">
      <SectionTitleVue title01="Featured" title02="Projects" />
      <div class="project-list">
        <ul>
          <li>
            <div class="info-box">
              <div class="icon"></div>
              <h2>나의 기억 저장소</h2>
              <h4 class="tag">Toy Project</h4>
              <p class="memo">
                모든 국민은 건강하고 쾌적한 환경에서 생활할 권리를 가지며, 국
                가와 국민은 환경보전을 위하여 노력하여야 한다. 국가는 균형있 는
                국민경제의 성장 및 안정과 적정한 소득의 분배를 유지하고, 시 장의
                지배와 경제력의 남용을 방지하며,
              </p>

              <div class="btn-list">
                <a href="/" class="github-btn"> Github </a>
                <a href="/" class="web-btn">WebSite</a>
              </div>
            </div>
            <div class="img-box">
              <img src="@/assets/images/mymemory.jpg" alt="mymemory" />
            </div>
          </li>

          <li>
            <div class="img-box">
              <img src="@/assets/images/mymemory.jpg" alt="mymemory" />
            </div>

            <div class="info-box">
              <div class="icon"></div>
              <h2>나의 기억 저장소</h2>
              <h4 class="tag">Toy Project</h4>
              <p class="memo">
                모든 국민은 건강하고 쾌적한 환경에서 생활할 권리를 가지며, 국
                가와 국민은 환경보전을 위하여 노력하여야 한다. 국가는 균형있 는
                국민경제의 성장 및 안정과 적정한 소득의 분배를 유지하고, 시 장의
                지배와 경제력의 남용을 방지하며,
              </p>

              <div class="btn-list">
                <a href="/" class="github-btn"> Github </a>
                <a href="/" class="web-btn">WebSite</a>
              </div>
            </div>
          </li>

          <li>
            <div class="info-box">
              <div class="icon"></div>
              <h2>나의 기억 저장소</h2>
              <h4 class="tag">Toy Project</h4>
              <p class="memo">
                모든 국민은 건강하고 쾌적한 환경에서 생활할 권리를 가지며, 국
                가와 국민은 환경보전을 위하여 노력하여야 한다. 국가는 균형있 는
                국민경제의 성장 및 안정과 적정한 소득의 분배를 유지하고, 시 장의
                지배와 경제력의 남용을 방지하며,
              </p>

              <div class="btn-list">
                <a href="/" class="github-btn"> Github </a>
                <a href="/" class="web-btn">WebSite</a>
              </div>
            </div>
            <div class="img-box">
              <img src="@/assets/images/mymemory.jpg" alt="mymemory" />
            </div>
          </li>
        </ul>

        <a href="" class="see-all-btn">See all projects</a>
      </div>
    </div>
  </section>
</template>

<script>
import SectionTitleVue from "../../common/SectionTitle.vue";
export default {
  components: { SectionTitleVue },
};
</script>

<style scoped>
.project-list {
  margin-top: 3rem;
}
.project-list li {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 10rem;
}
.project-list li .info-box {
  width: 42%;
}

.project-list li .info-box .icon {
  width: 60px;
  height: 60px;
  border-radius: 10px;
  background: #eee;
  margin-bottom: 1.2rem;
}
.project-list li .info-box h2 {
  font-size: 2.6rem;
  font-weight: 800;
  margin-bottom: 1rem;
  color: #7358d0;
}

.project-list li .info-box .tag {
  font-size: 1rem;
  font-weight: 400;
  color: #999;
  margin-bottom: 2.2rem;
}

.project-list li .info-box .memo {
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.6;
  margin-bottom: 3.5rem;
  color: #444;
}

.project-list li .info-box .btn-list {
  display: flex;
}

.project-list li .info-box .btn-list a {
  margin-right: 10px;
  display: flex;
  align-items: center;
  padding: 1.2rem 2.4rem;
  border-radius: 2rem;
  box-shadow: 4px 10px 25px rgba(102, 78, 104, 0.24);
  font-size: 0.94rem;
  font-weight: 600;
  transition: var(--transition);
}
.project-list li .info-box .btn-list a:hover {
  box-shadow: 5px 10px 20px rgba(255, 58, 118, 0.3);
  color: #ff3a76;
}

/* img-box */
.project-list li .img-box {
  width: 48%;
  height: 670px;
  background: #fff;
  border-radius: 30px;
  box-shadow: 4px 10px 25px rgba(102, 78, 104, 0.24);
  overflow: hidden;
}
.project-list li .img-box img {
  object-fit: cover;
  height: 100%;
}

.project-list .see-all-btn {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 320px;
  height: 74px;
  margin: 0 auto;
  font-size: 1.2rem;
  font-weight: 600;
  border-radius: 3rem;
  box-shadow: 4px 10px 25px rgba(102, 78, 104, 0.24);
}
</style>