<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
  </div>
</template>

<script type="text/ecmascript-6">
// 导入组件
import MHeader from 'components/m-header/m-header'
import Tab from 'components/tab/tab'

// 导出app根组件
export default {
  // 注册组件
  components: {
    MHeader,
    Tab
  }
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
</style>
