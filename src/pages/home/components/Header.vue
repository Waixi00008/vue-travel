<template>
  <div class="header">
    <div class="header-left"><span class="iconfont back-icon">&#xe624;</span></div>
    <div class="header-input">
      <span class="iconfont search-icon">&#xe632;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">城市<span class="iconfont arror-icon">&#xe64a;</span></div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~styles/variables.styl'
.header
  display flex
  height $headerHeight
  line-height $headerHeight
  background-color $bgColor
  color #fff
  .header-left
    float left
    width .72rem
    .back-icon
      display block
      text-align center
      font-size: .36rem
  .header-input
    flex 1
    margin .16rem 0
    padding-left .2rem
    height .48rem
    line-height .48rem
    border-radius 0.1rem
    color #ccc
    background-color #fff
    .search-icon
      vertical-align top
  .header-right
    float right
    min-width 1.20rem
    height 100%
    text-align center
    .arror-icon
      vertical-align top
      margin-left .04rem
      font-size: .24rem
</style>
