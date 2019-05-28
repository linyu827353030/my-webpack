<template>
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
    <home-footer></home-footer>
  </div>
</template>

<script>
import HomeHeader from "./components/Header";
import HomeSwiper from "./components/Swiper";
import HomeFooter from "./components/Footer";
export default {
  name: "Home",
  components: {
    HomeHeader,
    HomeSwiper,
    HomeFooter
  }
};
</script>

<style>
</style>