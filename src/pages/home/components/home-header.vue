<template>
  <div>
    <div class="header">
      <div class="header-left">
        <span class="iconfont iconLeft-"></span>
      </div>
      <div class="header-input">
        <span class="iconfont iconsousuo"></span>输入111
      </div>
      <router-link to="/city">
        <div class="header-right">
          <span class="iconfont iconDown-"></span>{{city}}
        </div>
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHerder',
  props: {
    city: String
  }
}
</script>

<style lang="stylus" scoped>
.header {
  display: flex;
  line-height: 0.86rem;
  background: #00bcd4;

  .header-left {
    width: 0.64rem;
  }

  .header-input {
    flex: 1;
    height: 0.64rem;
    line-height: 0.64rem;
    margin-top: 0.12rem;
    background: #FFFFFF;
  }

  .header-right {
    color: #fff;
    width: 1.24rem;
    text-align: center;
  }
}
</style>
