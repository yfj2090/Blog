<template>
  <div class="home-content-container">
    <div class="title">文章</div>
    <hr>
    <ul class="nav">
      <li><span>2018年11月01日 » </span><a href="#">测试测试测试测试测试测试测试</a></li>
      <li><span>2018年11月01日 » </span><a href="#">测试测试测试测试测试测试测试</a></li>
      <li><span>2018年11月01日 » </span><a href="#">测试测试测试测试测试测试测试</a></li>
      <li><span>2018年11月01日 » </span><a href="#">测试测试测试测试测试测试测试</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HomeContent',
  data() {

  }
}
</script>

<style lang="scss" scoped>
.home-content-container {
  width: 65%;
  .title {
    margin: 1rem 1rem 0;
    font-size: 1.285rem;
  }
  hr {
    margin: 1rem 1rem 0;
  }
  .nav {
    margin: 1rem 3rem;
    li {
      @include BaseFontSize(1rem);
      list-style-type: disc;

    }
  }
}</style>
