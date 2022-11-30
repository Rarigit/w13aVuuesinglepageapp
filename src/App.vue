<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HeaderProject/>
    <BodyProject/>
    <FooterProject/>
  </div>
</template>

<script>
import HeaderProject from "@/components/Header.vue";
import BodyProject from "@/components/Body.vue";
import FooterProject from "@/components/Footer.vue";

export default {
  name: "App",
  components :{
    HeaderProject,
    BodyProject,
    FooterProject
    }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
