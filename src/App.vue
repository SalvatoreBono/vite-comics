<script>
import TheFooter from "./components/TheFooter.vue";
import TheHeader from "./components/TheHeader.vue";
import TheMainBottom from "./components/TheMainBottom.vue";
import TheMainTop from "./components/TheMainTop.vue";

export default {
  components: {
    TheHeader,
    TheMainBottom,
    TheFooter,
    TheMainTop,
  },
};
</script>

<template>
  <TheHeader></TheHeader>
  <TheMainTop></TheMainTop>
  <TheMainBottom></TheMainBottom>
  <TheFooter></TheFooter>
</template>

<style lang="scss"></style>
