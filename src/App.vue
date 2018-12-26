<template>
  <div id="app">
    <vue-headful title="About Davie Lee" description="About Davie"/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import Footer from "@/components/Footer.vue";

export default {
  name: "home",
  components: {
    Footer
  }
};
</script>


<style>
@import url("https://fonts.googleapis.com/css?family=Work+Sans");

#app {
  font-family: "Work Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
