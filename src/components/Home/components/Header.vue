<template>
    <div class="header">
        <div class="header-back">
            <span class="iconfont back-icon">&#xe624;</span>
        </div>
        <div class="header-search">
            <span class="iconfont">&#xe632;</span>
            输入城市/景点/游玩主题
        </div>
        <div class="header-right">
        </div>
    </div>
</template>
<script>
export default{
  name: 'HomeHeader'
}
</script>
<style lang="stylus" scoped>
    .header
        height:.88rem;
        display:flex;
        background-color:#00bcd4
        .header-back
            width:.64rem;
            line-height:.88rem
            text-align:center
            .back-icon
                color:#fff
                font-weight:bold
                font-size:.36rem
        .header-search
            flex:1;
            background:#fff
            height:.64rem
            line-height:.64rem
            border-radius:.06rem
            margin-left:.2rem
            margin-top: .12rem
            padding:0 .2rem
        .header-right
            width:1.28rem;
</style>
