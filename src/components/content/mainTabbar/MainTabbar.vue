<template>
  <TabBar>
    <TabBarItem path="/home" activeColor="red">
      <img slot="item-icon" src="~assets/img/tabbar/home.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/home_active.svg" alt="">
      <div slot="item-text">首页</div>
    </TabBarItem>
    <TabBarItem path="cart" activeColor="red">
      <img slot="item-icon" src="~assets/img/tabbar/category.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/category_active.svg" alt="">
      <div slot="item-text">购物车</div>
    </TabBarItem>
    <TabBarItem path="category" activeColor="red">
      <img slot="item-icon" src="~assets/img/tabbar/shopcart.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/shopcart_active.svg" alt="">
      <div slot="item-text">分类</div>
    </TabBarItem>
    <TabBarItem path="profile" activeColor="red">
       <img slot="item-icon" src="~assets/img/tabbar/profile.svg" alt="">
       <img slot="item-icon-active" src="~assets/img/tabbar/profile_active.svg" alt="">
      <div slot="item-text">我的</div>
      <!-- <div slot="item-text">我的本地master测试测试</div> -->
      <!-- <div slot="item-text">我的test分支测试</div> -->
    </TabBarItem>
  </TabBar>
</template>

<script>
    import TabBarItem from 'components/common/tabbar/TabBarItem'
    import TabBar from 'components/common/tabbar/TabBar'
  export default {
    name: "MainTabbar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>
