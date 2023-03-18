<template>
  <img class="logo" src="../assets/JNU.png" />
  <el-text>暨南大学</el-text>
  <el-input v-model="input" placeholder="请输入想要搜索的商品" />
  <el-button color="#e62828" type="primary" :icon="Search">搜索</el-button>
</template>

<script lang="ts" setup>
import { ref } from 'vue'
import { Delete, Edit, Search, Share, Upload } from '@element-plus/icons-vue'
const input = ref('')
</script>
<style scoped>
img {
  width: 100px;
  height: 100px;
}
</style>