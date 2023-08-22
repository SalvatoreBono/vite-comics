<script>
export default {
  data() {
    return {
      listFooter: [
        {
          title: `DC COMICS`,
          credits: [
            `Character`,
            `Comics`,
            `Movies`,
            `TV`,
            `Games`,
            `Videos`,
            `News`,
          ],
        },
        {
          title: `DC`,
          credits: [
            `Terms of Use`,
            `Privacy policy (New)`,
            `Ad Choices`,
            `Advertising`,
            `Jobs`,
            `Subscriptioons`,
            `Talent WorkShops`,
            `CPSC Certificates`,
            `Ratings`,
            `Shop Help`,
            `Contact US`,
          ],
        },
        {
          title: `SITES`,
          credits: [
            `DC`,
            `MAD Magazine`,
            `DC Kids`,
            `DC Universe`,
            `DC Power Visa`,
          ],
        },
        {
          title: `SHOP`,
          credits: [`Shop DC`, `Shop DC Collectibles`],
        },
      ],
    };
  },
  methods: {},
};
</script>

<template>
  <footer>
    <div class="bg-dc">
      <div class="container text-white">
        <div class="d-flex justify-content-between">
          <div class="d-flex pt-5 pb-5">
            <div v-for="singleElement in listFooter" class="pe-5">
              <h4>{{ singleElement.title }}</h4>
              <ul class="me-auto mb-2 mb-lg-0 list-unstyled text-white">
                <li
                  v-for="singleCredits in singleElement.credits"
                  class="nav-item"
                >
                  <a class="nav-link" aria-current="page" href="#">{{
                    singleCredits
                  }}</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="logo-footer"></div>
        </div>
      </div>
    </div>
    <div class="footer-bg pt-4 pb-4">
      <div class="container d-flex justify-content-between">
        <button
          type="button"
          class="btn btn-outline-primary text-white btn-footer"
        >
          SIGN-UP NOW!
        </button>
        <div class="d-flex">
          <div class="d-flex align-items-center">
            <h5 class="color-primary">FOLLOW US</h5>
          </div>
          <div class="ps-4">
            <img src="../assets/img/footer-facebook.png" alt="" />
            <img src="../assets/img/footer-twitter.png" alt="" />
            <img src="../assets/img/footer-youtube.png" alt="" />
            <img src="../assets/img/footer-pinterest.png" alt="" />
            <img src="../assets/img/footer-periscope.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/variables" as *;
.bg-dc {
  background-image: url(../assets/img/footer-bg.jpg);
  background-repeat: repeat-x;
}
h4 {
  padding-bottom: 1rem;
}
li {
  color: rgb(149, 149, 149);
}
.logo-footer {
  background-image: url(../assets/img/dc-logo-bg.png);
  width: 600px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
.footer-bg {
  background-color: $bg-footer;
}
.btn-footer {
  border-radius: 0;
  border: 1.5px solid $color-primary;
}
.color-primary {
  color: $color-primary;
}
footer img {
  padding-right: 1rem;
}
</style>
