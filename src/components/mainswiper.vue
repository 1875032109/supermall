<template>
  <swiper>
    <swiper-item path="/home" activeColor="deepPink">
      <img slot="item-icon" src="~assets/img/tabbar/home.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/home_active.svg" alt="">
      <div slot="item-text">首页</div>
    </swiper-item>
    <swiper-item path="/category" activeColor="deepPink">
      <img slot="item-icon" src="~assets/img/tabbar/category.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/category_active.svg" alt="">
      <div slot="item-text">分类</div>
    </swiper-item>
    <swiper-item path="/profile" activeColor="deepPink">
      <img slot="item-icon" src="~assets/img/tabbar/profile.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/profile_active.svg" alt="">
      <div slot="item-text">我的</div>
    </swiper-item>
  </swiper>
</template>

<script>
  import swiper from "./swiper";
  import swiperitem from "./swiperitem";
  export default {
    name: "mainswiper",
    components: {
      swiper,
      swiperitem
    }
  }
</script>

<style scoped>

</style>
