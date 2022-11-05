<template>
  <div>
    <VueSlickCarousel v-bind="settings">
      <div><h3>1</h3></div>
      <div><h3>1</h3></div>
      <div><h3>1</h3></div>
    </VueSlickCarousel>
  </div>
</template>

<script>
export default {
  data() {
    return {
      settings: {
        dots: true,
        dotsClass: 'slick-dots custom-dot-class',
        edgeFriction: 0.35,
        infinite: true,
        speed: 500,
        slidesToShow: 2,
        slidesToScroll: 1,
      },
    }
  },
}
</script>

<style lang="scss" scoped></style>
