<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Title />
  </div>
</template>

<script>

import Title from "./components/Title.vue";

export default {
  name: "App",
  components: {
    Title,
  },
};
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
