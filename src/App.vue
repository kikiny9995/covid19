<template>
  <div id="app">
    <header-page></header-page>
    <div class="container">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
export default {
  name: "App",
  components: {
    "header-page": Header,
  },
};
</script>