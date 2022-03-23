<template>
  <div
    class="bg-item"
    :style="{ top: itemTop, left: itemLeft, opacity: itemOpacity }"
  ></div>
</template>

<script>
export default {
  props: {
    itemTop: String,
    itemLeft: String,
    itemOpacity: Number,
  },
};
</script>

<style scoped>
.bg-item {
  width: 20vw;
  height: 20vw;
  border-radius: 50%;
  background: var(--background-item-color);
  position: absolute;
  /* top: 50%;
  left: 30px;
  opacity: 0.5; */
  z-index: -1;
  filter: blur(50px);
}
</style>