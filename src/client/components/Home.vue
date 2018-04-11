<template>
  <div class="home-container">
    <p>{{msg}}</p>
    <br />
    <button @click="testFunction">testFunction()</button>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      msg: "Boilerplate for Express + Vue.JS with Typescript"
    };
  },
  methods: {
    testFunction() {
      alert("executed function");
    }
  },
  computed: {},
  created() {
    console.log("created hook");
  },
  mounted() {
    console.log("mounted hook");
  }
};
</script>

<style lang="scss" scoped>
.home-container {
  color: $primary;
  font-size: 16px;
}
</style>