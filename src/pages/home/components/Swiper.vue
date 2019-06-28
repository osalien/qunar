<template>
  <div class="wrapper">
    <swiper :options="swiperOption">
      <swiper-slide v-for='item of swiperList' :key='item.id'>
        <img class='swiper-image' :src='item.imgUrl' />
      </swiper-slide>
      <div class="swiper-pagination"  slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        loop: true
      },
      swiperList: [{
        id: '001',
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20196/c8de32c5ae7eea6b0d5e16aabff56266.jpg_750x200_4249f421.jpg'
      }, {
        id: '002',
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20196/3a3066c073a492c1a881607181ac84ab.jpg_750x200_ca7fff4c.jpg'
      }]
    }
  }
}
</script>

<style lang='stylus' scoped>
.wrapper >>> .swiper-pagination-bullet-active
  background: #fff
.wrapper
  overflow: hidden
  width: 100%
  height: 0
  padding-bottom: 26.8%
  background: #eee
  .swiper-image
    width: 100%
</style>
