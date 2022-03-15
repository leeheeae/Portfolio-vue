<template>
  <footer class="footer">
    <div class="container">
      <div class="text-box">
        <h2 class="main-text Averta">I look forward to hearing from you.</h2>
        <p class="sub-text">함께 성장해고자 하는 곳의 연락을 기다립니다.</p>
      </div>
      <div class="contact">
        <div class="email Averta">Chromeee@daum.net</div>
        <div class="number Averta">010-2332-5270</div>
      </div>

      <div class="sns">
        <div class="github"></div>
        <div class="github"></div>
        <div class="github"></div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10rem 2.4rem;
}
.text-box {
  text-align: center;
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
  margin: 0.6rem 0 4rem;
}
.contact {
  text-align: center;
}
.contact > div {
  display: inline-flex;
  font-size: 1.2rem;
  font-weight: 600;
  color: var(--gray-color-02);
  padding-bottom: 0.6rem;
  margin: 0 1.4rem 1.6rem 1.4rem;
  border-bottom: 2px solid var(--gray-color-01);
  transition: 0.3s;
}
.contact > div:hover {
  color: var(--white-color);
}
.sns {
  display: flex;
  justify-content: center;
}
.sns > div {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background: #fff;
  margin: 0 8px;
}
</style>