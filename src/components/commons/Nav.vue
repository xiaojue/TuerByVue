<template>
<nav class="nav">
  <div class="container">
    <div class="nav-left">
      <a class="nav-item">
		兔耳日记
      </a>
      <a class="nav-item is-tab is-hidden-mobile is-active">首页</a>
      <a class="nav-item is-tab is-hidden-mobile">发现</a>
      <a class="nav-item is-tab is-hidden-mobile">微信公众账号</a>
    </div>
    <span class="nav-toggle">
      <span></span>
      <span></span>
      <span></span>
    </span>
    <div class="nav-right nav-menu">
      <a class="nav-item is-tab is-hidden-tablet is-active">首页</a>
      <a class="nav-item is-tab is-hidden-tablet">发现</a>
      <a class="nav-item is-tab is-hidden-tablet">微信公众账号</a>
      <a class="nav-item is-tab">登入</a>
      <a class="nav-item is-tab">注册</a>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'nav',
  data: () => {
    return {

    }
  }
}
</script>
