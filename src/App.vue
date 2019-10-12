<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.svg" />
      <div class= "big-frame">
          <Shot msg="so nice" />
          <Shot msg="so nice" />
          <Shot msg="so nice" />
          <Shot msg="so nice" />
          <Shot msg="so nice" />
      </div>
  </div>
</template>

<script>
import Shot from "./components/Shot.vue";

export default {
  name: "app",
  components: {
    Shot
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.big-frame {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-evenly;
  align-items: flex-start;
}
</style>
