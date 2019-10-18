<template>
  <div>
    <div class="header">
      <div class="header-left">
        <span class="iconfont iconLeft-"></span>
      </div>
      <div class="header-input">
        <span class="iconfont iconsousuo"></span>输入
       </div>
      <div class="header-right">
        <span class="iconfont iconDown-"></span>城市
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHerder'
}
</script>

<style lang="stylus" scoped>
  .header
    display flex
    line-height: .86rem
    background: #00bcd4
    .header-left
      width: .64rem
    .header-input
      flex: 1
      height .64rem
      line-height .64rem
      margin-top .12rem
      background #FFFFFF
    .header-right
      width: 1.24rem
      text-align center
</style>
