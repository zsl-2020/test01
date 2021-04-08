<template>
  <div id="app">
    <div id="nav">
      <span>嘿嘿嘿 !!! </span>
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
      <router-link to="/about">About</router-link>
    </div>
    <!-- 路由出口 -->
    <router-view />
  </div>
</template>

<style lang="less">
@import 'assets/css/app.less';
</style>
