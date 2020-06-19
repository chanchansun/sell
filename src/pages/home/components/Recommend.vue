<template>
<div>
<div class="title">热销推荐</div>
    <ul>
        <li class="item border-bottom">
            <img class="item-img" src="../../../assets/images/picFive.png">
            <div class="item-info">
                <p class="item-title">大连圣亚海洋世界</p>
                <p class="item-desc">浪漫大连首战，浪漫的海洋主题公园</p>
                <button class="item-button">查看详情</button>
            </div>
        </li>
        <li class="item border-bottom">
            <img class="item-img" src="../../../assets/images/picFour.png">
            <div class="item-info">
                <p class="item-title">大连圣亚海洋世界</p>
                <p class="item-desc">浪漫大连首战，浪漫的海洋主题公园</p>
                <button class="item-button">查看详情</button>
            </div>
        </li>
        <li class="item border-bottom">
            <img class="item-img" src="../../../assets/images/picSix.png">
            <div class="item-info">
                <p class="item-title">大连圣亚海洋世界</p>
                <p class="item-desc">浪漫大连首战，浪漫的海洋主题公园</p>
                <button class="item-button">查看详情</button>
            </div>
        </li>
    </ul>
</div>
</template>

<script>
export default {
  name: 'HomeRecommend'
}
</script>

<style lang="stylus" scoped>
.title
  margin-top: .2rem
  line-height: .8rem
  background: #eee
  text-indent: .2rem
.item
  overflow:hidden
  display:flex
  height:1.9rem
  background:#eee
  .item-img
    width: 1.7rem
    height: 1.7rem
    padding: .1rem
  .item-info
    flex:1
    padding: .1rem
    .item-title
      line-height: .54rem
      font-size: .32rem
    .item-desc
      line-height: .4rem
      color:#ccc
    .item-button
      line-height:.44rem
      margin-top:.16rem
      background #ff9300
      padding:0 .2rem
      border-radius:.06rem
      color:#fff
</style>
