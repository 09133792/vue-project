<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <!-- 当前路由地址对应的内容 -->
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="stylus">
@import '~styles/varibles.styl';

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}

// .header-left{
//   position absolute;
//   top 2px;
//   left 8px;
// }

.commmonbgColor {
  background-color: $bgColor;
}
</style>
