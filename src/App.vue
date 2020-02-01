<template>
  <div id="app">
    <Header title="T.T Burger" subtitle="início" />
    <Content>
      <Imagem></Imagem>
    </Content>
  </div>
</template>

<script>

import Header from "./components/templates/Header";
import Content from "./components/templates/Content";
import Imagem from "./components/templates/Imagem";

export default {
  name: "App",
  components: {Header, Content, Imagem} 
}
</script>

<style>
  body {
    margin: 0;
  }

  #app{
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing:grayscale;

    height: 100vh;
    display: grid;

    grid-template-rows: 55px 1fr;
    grid-template-columns: 1fr;
    grid-template-areas:
    "header header"
    "content content";
  }
</style>