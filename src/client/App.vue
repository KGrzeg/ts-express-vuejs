<template>
  <div id="app">
    <img src="~assets/logo.png">
    <h1>{{msg}}</h1>
    <router-view/>
  </div>
</template>

<script>
export default {
  msg: "Hello World!"
};
</script>

<style lang="scss">
@import "~style/global.scss";

h1 {
  color: $secondary;
}
</style>
