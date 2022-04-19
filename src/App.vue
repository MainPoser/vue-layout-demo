<template>
  <el-container style="height: 100%">
    <el-header>Header</el-header>
    <el-main>
      <el-container style="height: 100%">
        <el-aside width="200px">Aside</el-aside>
        <el-main>Main</el-main>
      </el-container>
    </el-main>
    <el-footer></el-footer>
  </el-container>
</template>

<style lang="less">

html, body, #app {
  margin: 0;
  padding: 0;
  height: 100%;
}

.el-header {
  background: #42b983;
}

.el-aside {
  background: blue;
}

.el-main {
  background: darkred;
}

.el-footer {
  background: black;
}
</style>
