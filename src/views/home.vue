<template>
  <div class="wrap">
    <HomeHeader class="home-header" />
    <HomeContent class="home-content" />
  </div>
</template>

<script>
import HomeHeader from '@/views/components/header'
import HomeContent from '@/views/components/homeContent'
export default {
  components: {
    HomeHeader,
    HomeContent
  },
  data() {}
}
</script>

<style lang="scss" scoped>
.wrap {
  width: 50rem;
  margin: 0 auto;
  background: $grey-1;
  .home-header {
    float: left;
  }
  .home-content {
    float: left;
  }
}
</style>
