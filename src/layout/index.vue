<template>
  <div class="app-wrapper">
    <top-menu></top-menu>
    <side-bar></side-bar>
    <main-page></main-page>
  </div>
</template>

<script>
import TopMenu from '@/layout/topmenu/TopMenu'
import SideBar from '@/layout/sidebar/SideBar'
import MainPage from '@/layout/mainpage/MainPage'

export default {
  name: 'index',
  components: {
    TopMenu,
    SideBar,
    MainPage
  }
}
</script>

<style lang="css" scoped>
  .app-wrapper {
    height: 100%;
  }
</style>
