<template>
  <div id="app">
    <Title />
    <Hero />

  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";


export default {
  name: "App",
  components: {
    Title,
    Hero
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  margin-top: 50px;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
