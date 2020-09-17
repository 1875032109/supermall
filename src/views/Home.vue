<template>
  <swiper>
    <div slot="left">首页</div>
  </swiper>
</template>


<script>
  import swiper from "components/swiper";
  export default {
    name: "home",
    components: {
      swiper
    }
  }
</script>

<style scoped>
  @import url("//unpkg.com/element-ui@2.13.2/lib/theme-chalk/index.css");
  .el-header {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }

  .el-aside {
    background-color: #D3DCE6;
    color: #333;
    text-align: center;
    line-height: 200px;
  }

  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 160px;
  }

  body > .el-container {
    margin-bottom: 40px;
  }

  .swiper {
    display: flex;
    justify-content: space-around;
    align-items: center;
  }

  .swiper-list {
    flex: 1;
  }

  .swiper-list:hover {
    color: deeppink;
    cursor: pointer;
  }
</style>
