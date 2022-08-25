<!--
 * @Author: songren 732054167@qq.com
 * @Date: 2022-08-24 17:30:54
 * @FilePath: \peedy-ui\src\App.vue
 * @Description:
 * @LastEditors: songren 732054167@qq.com
 * @LastEditTime: 2022-08-25 09:56:23
-->
<template>
  <router-view />
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
