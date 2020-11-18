<template>
  <div>
    <my-header></my-header>
    <my-swiper></my-swiper>
  </div>
</template>

<script>
import MyHeader from "@/components/Header.vue";
import MySwiper from "@/components/Swiper.vue";
export default {
  name: "Home",
  components: {
    MyHeader,
    MySwiper
  },
};
</script>

<style>
</style>