<template>
  <nav>
    <ul>
      <li>aaaaaaa</li>
      <li>bbbbbbb</li>
      <router-link :to="{ name: 'routerTestSecond' }">次のページ</router-link>
    </ul>
  </nav>
</template>

<style scoped>
ul {
  list-style: none;
  padding: 0;
}
</style>