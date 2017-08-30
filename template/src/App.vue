<template>
  <div id="app">
    <img src="./assets/images/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
  mounted: function () {
    console.log('mounted')
  }
}
</script>

<style lang="less">
  @import '~@/style/common';
</style>
