<template>
  <div id="App">
    <tab-bar>
      <tab-bar-item>
        <template v-slot:item-text>
          首页
        </template>
      </tab-bar-item>
      <tab-bar-item>
        <template v-slot:item-text>
          分类
        </template>
      </tab-bar-item>
      <tab-bar-item>
        <template v-slot:item-text>
          购物车
        </template>
      </tab-bar-item>
      <tab-bar-item>
        <template v-slot:item-text>
          我的
        </template>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
  import TabBar from './components/content/tabbar/TabBar'
  import TabBarItem from "./components/content/tabbar/TabBarItem";

export default {
  name: 'App',
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style>
  @import './assets/css/base.css';
</style>
