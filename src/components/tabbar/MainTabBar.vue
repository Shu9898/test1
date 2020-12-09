<template>
  <div id="main-tab-bar">
    <tab-bar>
      <tab-bar-item path="/home" activeColor="#ffcc00">
<!--        <img slot="item-icon" src="../../assets/img/tabbar/nav2.png" alt="">-->
<!--        <img slot="item-icon" src="@/assets/img/tabbar/nav2.png" alt="">-->
        <img slot="item-icon" src="~assets/img/tabbar/nav2.png" alt="">
<!--        <img slot="item-icon-active" src="../../assets/img/tabbar/nav1.png" alt="">-->
<!--        <img slot="item-icon-active" src="@/assets/img/tabbar/nav1.png" alt="">-->
        <img slot="item-icon-active" src="~assets/img/tabbar/nav1.png" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="#ffcc00">
        <img slot="item-icon" src="../../assets/img/tabbar/nav2.png" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/nav1.png" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="#ffcc00">
        <img slot="item-icon" src="../../assets/img/tabbar/nav2.png" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/nav1.png" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="#ffcc00">
        <img slot="item-icon" src="../../assets/img/tabbar/nav2.png" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/nav1.png" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
  // import TabBar from "./TabBar";
  // import TabBarItem from "./TabBarItem";
  import TabBar from "components/tabbar/TabBar";
  import TabBarItem from "components/tabbar/TabBarItem";

    export default {
        name: "MainTabBar",
      components: {
        TabBar,
        TabBarItem
      }
    }
</script>

<style scoped>

</style>
