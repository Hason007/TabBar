<template>
  <div id="app">
    <router-view></router-view>
    <MainBar></MainBar>
  </div>
</template>

<script>
  import TabBar from "./components/tabbar/TabBar";
  import TabBarItem from "./components/tabbar/TabBarItem";
  import MainBar from "./components/tabbar/MainBar";
  export default {
    name:'App',
    components: {MainBar, TabBarItem, TabBar}
  }
</script>


<style>
  @import "assets/css/base.css";

</style>
