<script>
export default {
  data() {
    return {
      headerLink: [
        {
          link: `Characters`,
        },
      ],
    };
  },
  methods: {},
};
</script>

<template>
  <nav class="navbar bg-body-tertiary">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img
          src="../assets/img/dc-logo.png"
          alt="Bootstrap"
          width="60"
          height="60"
        />
      </a>
      <div>
        <ul class="d-flex me-auto mb-2 mb-lg-0 list-unstyled">
          <li v-for="singleLink in headerLink" class="nav-item text-uppercase">
            <a class="nav-link" aria-current="page" href="#">{{
              singleLink.link
            }}</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
li {
  padding-left: 1rem;
  padding-right: 1rem;
  font-weight: 700;
}
</style>
