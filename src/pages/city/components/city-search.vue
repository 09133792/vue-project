<template>
    <div>
        <div class="city-search">
            <input class="city-input" type="text" placeholder="请输入城市">
        </div>
    </div>
</template>

<script>
export default {
  name: 'city-search'
}
</script>

<style lang="stylus" scoped>
    .city-search{
        // background-color red;
        width 100%
        height 40px
    }
    .city-input
        text-align center
        width 94%
        height 30px
        padding 0 4px
        line-height 30px
        display block
        margin 6px auto 0
</style>
