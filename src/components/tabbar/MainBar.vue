<template>
  <tab-bar>

    <tab-bar-item path="/home">
      <div slot="item-icon"><img src="../../assets/imag/home.jpg"></div>
      <div slot="item-icon-active"><img src="../../assets/imag/home-active.jpg"></div>
      <div slot="item-text">首页</div>
    </tab-bar-item>

    <tab-bar-item path="/category">
      <div slot="item-icon"><img src="../../assets/imag/cart.jpg"></div>
      <div slot="item-icon-active"><img src="../../assets/imag/cart-active.jpg"></div>
      <div slot="item-text">分类</div>
    </tab-bar-item>

    <tab-bar-item path="/cart">
      <div slot="item-icon"><img src="../../assets/imag/category.jpg"></div>
      <div slot="item-icon-active"><img src="../../assets/imag/category-active.jpg"></div>
      <div slot="item-text">购物车</div>
    </tab-bar-item>

    <tab-bar-item path="/person">
      <div slot="item-icon"><img src="../../assets/imag/person.jpg"></div>
      <div slot="item-icon-active"><img src="../../assets/imag/person-active.jpg"></div>
      <div slot="item-text">个人</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from "./TabBar";
  import TabBarItem from "./TabBarItem";

  export default {
    name: "MainBar",
    components:{
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>