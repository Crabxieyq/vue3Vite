<!--
 * @Descripttion: 
 * @version: 
 * @Author: yanqing.Xie
 * @Date: 2023-12-13 16:59:36
 * @LastEditors: yanqing.Xie
 * @LastEditTime: 2023-12-13 17:51:09
-->
<script setup lang="ts">
</script>

<template>
  <div>
    <!-- src/components/HelloWorld.vue -->
    <div>
      <el-button type="success"><i-ep-SuccessFilled />Success</el-button>
      <el-button type="info"><i-ep-InfoFilled />Info</el-button>
      <el-button type="warning"><i-ep-WarningFilled />Warning</el-button>
      <el-button type="danger"><i-ep-WarnTriangleFilled />Danger</el-button>
    </div>

    <h1>根组件</h1>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
