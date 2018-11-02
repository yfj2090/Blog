<template>
  <div class="header-container">
    <a href="../index.vue" class="logo">Blog</a>
    <ul class="nav">
      <li><a href="../index.vue">首页</a></li>
      <li><a href="">记录</a></li>
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
  .logo {
    color: $grey-6;
    @include BaseFontSize(100px);

  }
  .nav {
    display: inline-block;
    li {
      display: inline-block;
    }
  }
}
</style>
