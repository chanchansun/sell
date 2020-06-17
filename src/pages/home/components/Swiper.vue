<template>
<div class="wrapper">
  <swiper :options="swiperOptions">
    <swiper-slide >
      <img class="swiper-img" src="../../../assets/images/picEight.jpg"/>
    </swiper-slide>
    <swiper-slide >
      <img class="swiper-img" src="../../../assets/images/picNine.jpg"/>
    </swiper-slide>
    <div class="swiper-pagination" slot="pagination"></div>
  </swiper>
</div>

</template>

<script>
export default{
  name: 'HomeSwiper',
  data () {
    return {
      swiperOptions: {
        pagination: '.swiper-pagination'
      }
    }
  }
}
</script>
<style lang="stylus" scope>
  .wrapper
    overflow:hidden
    width:100%
    background: #eee
    .swiper-img
      width:100%
</style>
