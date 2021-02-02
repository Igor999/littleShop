<template>
  <div id="app">
    <Shop shop-title="Смартфоны" />
    <shop shop-title="Ноутбуки" />
  </div>
</template>

<script>
  import Shop from "./components/Shop";

  export default {
    components: {
      Shop
    }
  }
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
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
