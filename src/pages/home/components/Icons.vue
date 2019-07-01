<template>
    <div class="icons">
      <swiper :options="swiperOption">
        <swiper-slide>
          <div class="icon">
            <div class="icon-img">
              <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png"/>
            </div>
            <p class="icon-desc">热门景点</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="icon">
            <div class="icon-img">
              <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/3e/86314b2af03b7502.png"/>
            </div>
            <p class="icon-desc">水上乐园</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="icon">
            <div class="icon-img">
              <img class="icon-img-content" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/3ef092d0a89ffddb7f781cda30c8ae49.png"/>
            </div>
            <p class="icon-desc">魔都上海</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="icon">
            <div class="icon-img">
              <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/f5/c4c9d9830404e602.png"/>
            </div>
            <p class="icon-desc">室内娱乐</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="icon">
            <div class="icon-img">
              <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/76/eb88861d78fb9902.png"/>
            </div>
            <p class="icon-desc">动植物园</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="icon">
            <div class="icon-img">
              <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/8246f27355943202.png"/>
            </div>
            <p class="icon-desc">世纪公园</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="icon">
            <div class="icon-img">
              <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/47/c2b659e048b11602.png"/>
            </div>
            <p class="icon-desc">上海野生</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="icon">
            <div class="icon-img">
              <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/de/f26be47a6bf02a02.png"/>
            </div>
            <p class="icon-desc">上海迪士尼</p>
          </div>
        </swiper-slide>
      </swiper>
    </div>
</template>

<script>
export default {
  name: 'HomeIcons'
}
</script>

<style lang='stylus' scoped>
  @import '~styles/varibles.styl';
  .icons
    overflow: hidden
    height: 0
    padding-bottom: 50%
    .icon
      position: relative
      overflow: hidden
      float: left
      width: 25%
      height: 0
      padding-bottom: 25%
      .icon-img
        position: absolute
        top: 0
        left: 0
        right: 0
        bottom: .44rem
        box-sizing: border-box
        padding: .1rem
        .icon-img-content
          display: block
          margin: 0 auto
          height: 100%
      .icon-desc
        position: absolute
        left: 0
        right: 0
        bottom: 0
        height: .44rem
        line-height: .44rem
        text-align: center
        color: darkTexkColor
</style>
