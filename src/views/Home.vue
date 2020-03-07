<template>
  <div class="home">
    <el-container>
      <el-header>Header</el-header>
      <el-container>
        <el-aside width="200px">Aside</el-aside>
        <el-main>Main</el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>


export default {
  name: 'Home',
  components: {
  }
}
</script>

<style lang="scss">
  .home {
    height: 100%;
    .el-container {
      height: 100%;
      .el-aside {
        background: aqua;
        height: 100%;
      }
      .el-main {
        background: antiquewhite;
      }
    }
  }
</style>
