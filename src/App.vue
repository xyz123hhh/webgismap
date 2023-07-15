<template>
  <div id="app">
    <el-container class="app-Out-Pannel">
      <el-header class="sys-header">一张图项目系统</el-header>
      <el-container clss="app-Content-Pannel">
        <el-aside width="200px" class="sys-menu">左侧菜单</el-aside>
        <el-main>地图区域</el-main>
      </el-container>
    </el-container>

  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue' 不用了（4.项目需求）

export default {
  name: 'App',
  components: {}
}
</script>

<style>
html,
body,
#app {
  position: relative;
  width: 100%;
  height: 100%;
  margin: 0;
}

.app-Out-Pannel,
.app-Content-Pannel {
  height: 100%;
}

.sys-header {
  background-color: #409EFF;
  line-height: 60px;
  color: #fff;
  font-size: 20px;
}

.sys-menu {
  background-color: #C0C4CC;
}
</style>
