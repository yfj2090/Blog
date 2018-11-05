<template>
  <div class="header-container">
    <a href="../index.vue" class="logo">网络日志</a>
    <ul class="nav">
      <li><a href="../index.vue">首页</a></li>
      <li><a href="">记录</a></li>
      <li><a href="">关于我</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data() {

  }
}
</script>

<style lang="scss" scoped>
.header-container {
  width: 25%;
  .logo {
    display: block;
    padding: 3rem 0;
    background: $mainColor1;
    color: $grey-1;
    font-size: $defaultFontSize4;
    text-align: center;
  }
  .nav {
    li {
      line-height: 2rem;
      font-size: 1rem;
      text-align: center;
      a {
        display: block;
        color: $titleBlack;
      }
      a:hover {
        background: $grey-2;
      }
    }
  }
}</style>
