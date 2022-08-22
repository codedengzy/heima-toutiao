<!--
 * @Author: codedzy
 * @Date: 2022-08-02 21:23:32
 * @LastEditTime: 2022-08-02 21:40:01
 * @Description:
-->
<template>
  <div id="app">
    <router-view />
    <h1>移动端头条</h1>
    <div>
      <i class="iconfont icon-shoucang"></i>
      <van-button type="primary">主要按钮</van-button>
      <van-button type="info">信息按钮</van-button>
      <van-button type="default">默认按钮</van-button>
      <van-button type="warning">警告按钮</van-button>
      <van-button type="danger">危险按钮</van-button>
    </div>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>
<style lang="less">
</style>
