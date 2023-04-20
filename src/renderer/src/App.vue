<script setup lang="ts">
import sidebar from './components/sidebar.vue'
</script>

<template>
  <div class="main">
    <div class="sidebar-container">
      <sidebar></sidebar>
    </div>
    <div class="page-container"></div>
  </div>
</template>

<style lang="less">
@import './assets/css/styles.less';
</style>
