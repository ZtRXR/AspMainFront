<script setup>

</script>

<template>
  <el-menu
      default-active="/"
      class="el-menu-vertical-demo"
      :router="true"
  >
    <!--      @open="handleOpen"-->
    <!--      @close="handleClose"-->
    <el-menu-item index="/">
      <el-icon>
        <el-icon>
          <House/>
        </el-icon>
      </el-icon>
      <span>主页</span>
    </el-menu-item>
    <el-menu-item index="/gibberish">
      <el-icon>
        <Service/>
      </el-icon>
      <span>乱语</span>
    </el-menu-item>
    <!--    <el-sub-menu index="1">-->
    <!--      <template #title>-->
    <!--        <el-icon><location /></el-icon>-->
    <!--        <span>Navigator One</span>-->
    <!--      </template>-->
    <!--      <el-menu-item-group title="Group One">-->
    <!--        <el-menu-item index="1-1">item one</el-menu-item>-->
    <!--        <el-menu-item index="1-2">item two</el-menu-item>-->
    <!--      </el-menu-item-group>-->
    <!--      <el-menu-item-group title="Group Two">-->
    <!--        <el-menu-item index="1-3">item three</el-menu-item>-->
    <!--      </el-menu-item-group>-->
    <!--      <el-sub-menu index="1-4">-->
    <!--        <template #title>item four</template>-->
    <!--        <el-menu-item index="1-4-1">item one</el-menu-item>-->
    <!--      </el-sub-menu>-->
    <!--    </el-sub-menu>-->
    <!--    <el-menu-item index="2">-->
    <!--      <el-icon><icon-menu /></el-icon>-->
    <!--      <span>Navigator Two</span>-->
    <!--    </el-menu-item>-->
    <!--    <el-menu-item index="3" disabled>-->
    <!--      <el-icon><document /></el-icon>-->
    <!--      <span>Navigator Three</span>-->
    <!--    </el-menu-item>-->
    <!--    <el-menu-item index="4">-->
    <!--      <el-icon><setting /></el-icon>-->
    <!--      <span>Navigator Four</span>-->
    <!--    </el-menu-item>-->
  </el-menu>
</template>

<style scoped>
.el-menu {
  width: 100px;
}
</style>