<script>
export default {};
</script>

<template>
  <footer>
    <div class="bg-dc">
      <div class="container text-white">
        <div class="d-flex justify-content-between">
          <div class="d-flex pt-5 pb-0">
            <div class="pe-5">
              <h4>DC COMICS</h4>
              <ul class="me-auto mb-2 mb-lg-0 list-unstyled text-white">
                <li class="nav-item">
                  <a class="nav-link" aria-current="page" href="#"
                    >Characters</a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Comics</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Movies</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">TV</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Games</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Videos</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">News</a>
                </li>
              </ul>
              <div class="pe-0 pt-4 pb-5">
                <h4>SHOP</h4>
                <ul class="me-auto mb-2 mb-lg-0 list-unstyled text-white">
                  <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="#">Shop DC</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Shop DC Collectibles</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="pe-5">
              <h4>DC</h4>
              <ul class="me-auto mb-2 mb-lg-0 list-unstyled text-white">
                <li class="nav-item">
                  <a class="nav-link" aria-current="page" href="#"
                    >Terms of Use</a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Privacy policy (New)</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Ad Choices</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Advertising</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Jobs</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Subcriptions</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Talent WorkShops</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">CPSC Certificates</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Ratings</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Shop Help</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Contact Us</a>
                </li>
              </ul>
            </div>
            <div>
              <h4>SITES</h4>
              <ul class="me-auto mb-2 mb-lg-0 list-unstyled text-white">
                <li class="nav-item">
                  <a class="nav-link" aria-current="page" href="#">DC</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">MAD Magazine</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">DC Kids</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">DC Universe</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">DC Power Visa</a>
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
