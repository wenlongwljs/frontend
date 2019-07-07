<template>
  <div class="main-page-wrapper">
    <page-tabs></page-tabs>
  </div>
</template>

<script>
import PageTabs from './PageTabs'
export default {
  name: 'Main',
  components: {
    PageTabs
  }
}
</script>

<style scoped>
  .main-page-wrapper {
    margin-left: 220px;
    /* 去掉下边滚动条 */
    overflow: hidden;
  }
</style>
