<template>
  <tab-bar>
    <tab-bar-item>
      <img slot="item-icon" src="../assets/img/tabbar/home.svg">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item>
      <img slot="item-icon" src="../assets/img/tabbar/category.svg">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item>
      <img slot="item-icon" src="../assets/img/tabbar/shopcart.svg">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item>
      <img slot="item-icon" src="../assets/img/tabbar/profile.svg">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from '../components/tabbar/TabBar.vue'
  import TabBarItem from '../components/tabbar/TabBarI-item.vue'

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
