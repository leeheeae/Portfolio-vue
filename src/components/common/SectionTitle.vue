<template>
  <div class="section-title">
    <h1>{{ title01 }}</h1>
    <h1>{{ title02 }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    title01: String,
    title02: String,
  },
};
</script>

<style scoped>
.section-title h1 {
  font-size: 4.4rem;
  font-weight: 800;
  user-select: none;
}
.section-title h1:nth-child(1) {
  color: transparent;
  -webkit-text-stroke: 1px #000;
  margin-bottom: 6px;
}
</style>