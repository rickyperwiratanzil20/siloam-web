<template>
  <Header></Header>
  <Main></Main>
  <Footer></Footer>
</template>

<script>
import Header from "./components/molecule/Header.vue";
import Main from "./components/molecule/Main.vue";
import Footer from "./components/molecule/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style>
/* Body */
* {
  margin: 0 auto;
  font-family: Mulish, sans-serif;
  font-size: 12px;
}
body {
  width: 1300px;
}
</style>
