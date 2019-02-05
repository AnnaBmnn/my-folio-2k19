<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import "~@/assets/scss/_reset.scss";
@import "~@/assets/scss/_fonts.scss";
// @import "~@/assets/scss/_fonts.scss";
// 
#app {
  font-family: "Monument Extended", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  min-height: 100vh;
  background-color: #2a472e;
  color: #DA7A7A;
}
#nav {
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
