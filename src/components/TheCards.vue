<script>
export default {
  props: {
    imgSrc: String,

    seriesTitle: {
      type: String,
      required: true,
    },
  },
};
</script>

<template>
  <img :src="imgSrc" alt="" />
  <div class="pt-3 text-uppercase">{{ seriesTitle }}</div>
</template>

<style lang="scss" scoped>
img {
  width: 100%;
  height: 100%;
  aspect-ratio: 1/1;
}
</style>
