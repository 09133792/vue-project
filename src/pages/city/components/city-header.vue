<template>
  <div>
    <div class="city-header border-bottom">
      <router-link
        class="header-left"
        to="/"
      >
        <span class="iconfont iconLeft-"></span>
      </router-link>
      <span>城市选择</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'city-header'
}
</script>

<style lang="stylus" scoped>
.city-header {
  text-align: center;
  height: 34px;
  line-height: 34px;
}

.header-left {
  position absolute;
  top 2px;
  left 8px;
  color #fff;
}
</style>
