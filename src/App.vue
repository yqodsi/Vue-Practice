<template>
  <div id="app">
    <SkillsList msg="Hello" />
  </div>
</template>

<script>
import SkillsList from "./components/SkillsList.vue";
export default {
  name: "app",
  components: {
    SkillsList,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Montserrat:400,700");

body {
  background-color: #eeeeee;
  font-family: "Montserrat", sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  align-items: center;
}
body,
html {
  margin: 0;
  height: 100%;
}
#app {
  width: 50%;
}
</style>
