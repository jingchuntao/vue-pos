<template>
<div class="left-nav">
<ul>
  <li>
    <i class="icon iconfont icon-liebiao"></i>
    <div>列表</div>
  </li>
  <li>
    <i class="icon iconfont icon-rectangle390"></i>
    <div>支付</div>
  </li>
  <li>
    <i class="icon iconfont icon-wode"></i>
    <div>我的</div>
  </li>
  <li>
    <i class="icon iconfont icon-shezhi"></i>
    <div>设置</div>
  </li>
</ul>
</div>
</template>

<script>
export default {
  name: 'leftNav'
}
</script>

<style>
.left-nav{
  color: #fff;
  font-size: 10px;
  height: 100%;
  background-color: #1d8ce0;
  float: left;
  width: 5%;
}
  .iconfont{
    font-size: 24px;
  }
  .left-nav ul{
    padding: 0;
    margin: 0;
  }
  .left-nav li{
    list-style: none;
    text-align: center;
    border-bottom: 1px solid #20a0ff;
    padding: 10px;
  }

</style>
