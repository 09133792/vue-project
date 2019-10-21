<template>
  <div>
    <div class="commmonbgColor">
      <city-header></city-header>
      <city-search></city-search>
    </div>

  </div>
</template>

<script>
import cityHeader from '@/pages/city/components/city-header'
import citySearch from '@/pages/city/components/city-search'
export default {
  name: 'city',
  components: {
    cityHeader,
    citySearch
  }
}
</script>

<style lang="stylus" scoped>
</style>
