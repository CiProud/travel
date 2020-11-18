<template>
  <swiper ref="MySwiper" :options="swiperOptions">
    <swiper-slide>
        <img src="" />
    </swiper-slide>
    <swiper-slide>Slide 2</swiper-slide>
    <swiper-slide>Slide 3</swiper-slide>
    <div class="swiper-pagination" slot="pagination"></div>
  </swiper>
</template>

<script>
export default {
  name: "MySwiper",
};
</script>

<style scoped>
</style>