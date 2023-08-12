<script setup>

import ASide from "@/views/Apps/ASide.vue";
</script>
<template>
  <div class="common-layout">
    <el-container>
      <el-header style="height: 40px;display: flex;justify-content: center">
        <el-text type="success" style="font-size: large">
          Zengtudor Web
        </el-text>
      </el-header>
      <el-container>
        <el-aside width="200px">
          <ASide></ASide>
        </el-aside>
        <el-container>
          <el-main><RouterView/></el-main>
          <el-footer>
            <el-text type="info" style="display: flex;justify-content: center">作者:曾子愚 技术:Vue3,Vite,route,ElementUI...</el-text>
          </el-footer>
        </el-container>
      </el-container>
    </el-container>
  </div>
</template>


<style scoped>

</style>