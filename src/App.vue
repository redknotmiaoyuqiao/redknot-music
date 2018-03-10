<template>
  <div id="app">
    <MHeader></MHeader>
    <Tab></Tab>
    <router-view></router-view>
  </div>
</template>

<script>

import MHeader from 'components/m-header/m-header.vue'
import Tab from 'components/tab/tab.vue'

export default {
  name: 'App',
  components: {
    MHeader,
    Tab
  }
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
@import '~common/stylus/variable.styl'

#app
  color : $color-theme
</style>
