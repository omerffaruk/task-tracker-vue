<template>
  <div class="container">
    <PageHeader />
    <HomePage />
    <PageFooter />
  </div>
</template>
<script>
import PageHeader from "./components/PageHeader.vue";
import HomePage from "./components/HomePage.vue";
import PageFooter from "./components/PageFooter.vue";

export default {
  name: "App",
  components: {
    PageHeader,
    HomePage,
    PageFooter,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  padding: 0;
  margin: 0;
}
</style>
