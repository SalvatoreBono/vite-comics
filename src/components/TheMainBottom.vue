<script>
export default {};
</script>

<template>
  <div class="bg-main-bottom">
    <div class="container text-white pt-5 pb-5">
      <div class="main-bottom">
        <div class="d-flex align-items-center">
          <img
            class="pe-3"
            src="../assets/img/buy-comics-digital-comics.png"
            alt=""
          />
          <div>DIGITAL COMICS</div>
        </div>
        <div class="d-flex align-items-center">
          <img
            class="pe-3"
            src="../assets/img/buy-comics-merchandise.png"
            alt=""
          />
          <div>DC MERCHANDISE</div>
        </div>
        <div class="d-flex align-items-center">
          <img
            class="pe-3"
            src="../assets/img/buy-comics-subscriptions.png"
            alt=""
          />
          <div>SUBSCRIPTION</div>
        </div>
        <div class="d-flex align-items-center">
          <img
            class="pe-3"
            src="../assets/img/buy-comics-shop-locator.png"
            alt=""
          />
          <div>COMIC SHOP LOCATOR</div>
        </div>
        <div class="d-flex align-items-center">
          <img
            class="pe-3"
            src="../assets/img/buy-comics-shop-locator.png"
            alt=""
          />
          <div>DC POWER VISA</div>
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
