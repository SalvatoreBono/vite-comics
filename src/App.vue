<script>
import TheFooter from "./components/TheFooter.vue";
import TheHeader from "./components/TheHeader.vue";
import TheMainBottom from "./components/TheMainBottom.vue";

export default {
  components: {
    TheHeader,
    TheMainBottom,
    TheFooter,
  },
};
</script>

<template>
  <TheHeader></TheHeader>
  <TheMainBottom></TheMainBottom>
  <TheFooter></TheFooter>
</template>

<style lang="scss"></style>
