<template>
  <div class="swiper">
    <div class="swiper-item" @click="pageChange(path)">首页</div>
    <div class="swiper-item" @click="pageChange(path)">分类</div>
    <div class="swiper-item" @click="pageChange(path)">我的</div>
  </div>
</template>
<script>
  export default {
    name: "mainswiper",
    components: {
    },
    data() {
      return {
        path: null
      }
    },
    methods: {
      pageChange: {

      }
    }
  }
</script>

<style scoped>
  .swiper {
    display: flex;
    justify-content: space-around;
    align-items: center;
  }

  .swiper-item {
    flex: 1;
    text-align: center;
    height: 49px;
    font-size: 14px;
  }
</style>
