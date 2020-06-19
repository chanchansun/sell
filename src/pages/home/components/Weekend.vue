<template>
<div>
<div class="title">周末去哪儿</div>
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
  name: 'HomeWeekend'
}
</script>

<style lang="stylus" scoped>
.title
  margin-top: .2rem
  line-height: .8rem
  background: #eee
  text-indent: .2rem
.item-img-wrapper
  overflow:hidden
  height:0
  padding-bottom:33.9%
.item-img
  width:100%
.item-info
  padding: .1rem
  .item-title
    line-height: .54rem
    font-size: .32rem
  .item-desc
    line-height: .4rem
    color:#ccc
</style>
