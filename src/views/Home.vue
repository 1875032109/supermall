<template>
  <div id="home">
    <div>
      <el-container style="height: 500px; border: 1px solid #eee">
        <el-aside width="200px" style="background-color: rgb(238, 241, 246)">Aside</el-aside>
        <el-container>
          <el-header>
            <mainswiper/>
          </el-header>
          <el-main>
            <div>
              <category/>
              <profile/>
            </div>


          </el-main>
        </el-container>
      </el-container>
    </div>
<!--    <router-view/>-->
  </div>
</template>


<script>
  import mainswiper from "../components/mainswiper";
  import Category from "./Category";
  import Profile from "./Profile";
  export default {
    name: "home",
    components: {
      mainswiper,
      Category,
      Profile
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
</style>
