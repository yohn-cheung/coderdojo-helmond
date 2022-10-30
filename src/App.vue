<script setup>
import { RouterView } from "vue-router";
import NavBar from "@/components/navbar.vue";
import Banner from "@/components/banner.vue";
import Footer from "@/components/footer.vue";
</script>

<template>
  <NavBar />

  <Banner />

  <RouterView />

  <Footer />
</template>

<style>
body {
  font-family: "Open Sans", sans-serif;
}
/*create colomns*/
.col-sm-12.colomns {
  -webkit-column-count: 2;
  /* Chrome, Safari, Opera */
  -moz-column-count: 2;
  /* Firefox */
  column-count: 2;

  -webkit-column-gap: 2.5em;
  /* Chrome, Safari, Opera */
  -moz-column-gap: 2.5em;
  /* Firefox */
  column-gap: 2.5em;
}

@media (max-width: 575px) {
  .col-sm-12.colomns {
    -webkit-column-count: 1;
    /* Chrome, Safari, Opera */
    -moz-column-count: 1;
    /* Firefox */
    column-count: 1;
  }
}
</style>
