<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style lang="less">
  @import '~@/assets/style/h5/index.less';

  .container {
    padding: 20px;
  }
</style>
