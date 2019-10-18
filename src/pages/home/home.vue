<template>
  <div>
   <!-- <div>home</div>
    <router-link to="/list">去列表</router-link> -->
    <home-header></home-header>
  </div>
</template>

<script>
import HomeHeader from './components/header.vue'
export default {
  name: 'Home',
  components: {
    HomeHeader
  }
}
</script>

<style>

</style>
