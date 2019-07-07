<template>
  <div class="top-menu">
    <div class="top-menu-logo">北京龙软科技股份有限公司</div>
    <div class="top-menu-item active">安全监测</div>
    <div class="top-menu-item">人员定位</div>
    <div class="top-menu-item">瓦斯抽采</div>
    <div class="top-menu-item">系统管理</div>
  </div>
</template>

<script>
export default {
  name: 'TopMenu'
}
</script>

<style scoped>
  .top-menu {
    display: flex;
    flex-flow: row wrap;
    width: 100%;
    background-color: #007bff;
  }
  .top-menu-logo {
    width: 220px;
    height: 33px;
    line-height: 33px;
    text-align: center;
  }
  .top-menu-item {
    width: 120px;
    height: 33px;
    line-height: 33px;
    text-align: center;
    background-color: #17a2b8;
  }
  .active {
    background-color: #6f42c1;
  }
</style>
