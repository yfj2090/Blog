<template>
  <div class="wrap">
    <HomeHeader/>
  </div>
</template>

<script>
import HomeHeader from '@/views/components/header'
export default {
  components: {
    HomeHeader
  },
  data() {

  }
}
</script>

<style lang="scss" scoped>
.wrap {
  width: 800px;
  margin: 0 auto;
}
</style>
