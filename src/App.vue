<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Title />
    <Hero />
  </div>
</template>

<script>
import Title from "@/components/Title.vue";
import Hero from "@/components/Hero.vue";

export default {
  name: "App",
  components: {
    Title,
    Hero,
  },
};
</script>

<style lang="scss">
body {
  background-color: rgb(221, 255, 251);
}
img {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 100px;
  padding-top: 160px;
}
</style>
