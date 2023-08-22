<script>
export default {
  data() {
    return {
      titleImg: [
        {
          title: `digital comics`,
          img: `buy-comics-digital-comics.png`,
        },
        {
          title: `dc merchandise`,
          img: `buy-comics-merchandise.png`,
        },
        {
          title: `subscription`,
          img: `buy-comics-subscriptions.png`,
        },
        {
          title: `comic shop locator`,
          img: `buy-comics-shop-locator.png`,
        },
        {
          title: `dc power visa`,
          img: `buy-comics-subscriptions.png`,
        },
      ],
    };
  },
  methods: {},
};
</script>

<template>
  <div class="bg-main-bottom">
    <div class="container text-white pt-5 pb-5">
      <div class="main-bottom">
        <div v-for="singleImg in titleImg" class="d-flex align-items-center">
          <img class="pe-3" :src="`/src/assets/img/${singleImg.img}`" alt="" />
          <div class="text-uppercase">{{ singleImg.title }}</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/variables" as *;
.bg-main-bottom {
  background-color: $color-primary;
}
img {
  width: calc(100% / 5);
}
.main-bottom {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
</style>
