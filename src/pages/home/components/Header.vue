<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-ico">&#xe630;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe607;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont arrow-icon">&#xe609;</span>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Header'
}
</script>
<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .header
    display: flex
    line-height .86rem
    background: $bgColor
    color: #ffffff
    .header-left
      width: .64rem
      flex: left
      .back-ico
        text-align center
        font-size: .4rem
    .header-input
      flex:1
      line-height: .64rem
      height .64rem
      margin-top: .12rem
      margin-left .2rem
      color:#ccc
      background #fff
      border-radius .1rem
      padding-left :.2rem
    .header-right
      width 1.24rem
      float: right
      text-align: center
      .arrow-icon
        margin-left: -.04rem
        font-size: .24rem
</style>
