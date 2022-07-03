<template>
  <div>
    <h2>テストページ1</h2>
    <router-link :to="{ name: 'routerTestSecond' }">次のページ</router-link>
  </div>
  
  <NavList/>
</template>

<script>
import NavList from '@/components/navList.vue'

export default ({
  components: {
    NavList
  }
})
</script>

<style scoped lang="scss">
h2 {
  font-size: 100px;
}
</style>