<script>
import TheCard from "../components/TheCards.vue";
import dcComics from "../db/dc-comics.json";

export default {
  data() {
    return {
      dcComics,
    };
  },
  components: {
    TheCard,
  },
};
</script>

<template>
  <div class="jumbo"></div>
  <div class="bg-dark">
    <div class="container position-relative">
      <div class="container-series text-white bg-primary p-2">
        <h3 class="title-series">CURRENT SERIES</h3>
      </div>
      <div class="pt-5 text-white pb-3">
        <div class="row row-cols-6 gy-5">
          <div v-for="singleComics in dcComics" class="col pb-5">
            <TheCard
              :img-src="singleComics.thumb"
              :series-title="singleComics.series"
            ></TheCard>
          </div>
          <button
            type="button"
            class="btn btn-primary m-auto mt-5 rounded-0 fw-bold"
          >
            LOAD MORE
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.jumbo {
  background-image: url(../assets/img/jumbotron.jpg);
  background-size: cover;
  height: 400px;
}
.container-series {
  position: absolute;
  top: -30px;
}
img {
  width: 100%;
  height: 100%;
  aspect-ratio: 1/1;
}
.title-series {
  font-weight: 600;
}
</style>
