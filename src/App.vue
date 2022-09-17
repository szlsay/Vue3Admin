<template>
  <nav>
    <svg-icon icon="user" />
    <span class="svg-container">
      <svg-icon icon="user" />
    </span>
    <span class="svg-container">
      <svg-icon icon="https://res.lgdsunday.club/user.svg"></svg-icon>
    </span>
  </nav>
  <!-- <router-view/> -->
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
