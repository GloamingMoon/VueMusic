<template>
  <div id="app">
    hello world
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "common/stylus/variable"
  #app
    color:$color-theme

</style>
