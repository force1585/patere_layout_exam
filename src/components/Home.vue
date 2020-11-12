<template>
  <div id="app">
    <Header />
    <Main />
    <List />
    <Footer />
  </div>
</template>

<script>
import Header from "./Header";
import Footer from "./Footer";
import Main from "./MainContent";
import List from "./List";

export default {
  name: "Home",
  components: {
    Header,
    Footer,
    Main,
    List
  }
};
</script>

<style>
*{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  box-sizing:border-box;
  margin:0;
}
</style>
