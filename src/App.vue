<template>
  <div>
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  /* background-image: ; */
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-image: url("./assets/Group.png");
  /* ../assets/Design.png */
}

.title {
  text-align: center;
  padding: 35px 0 55px 0;
  font-family: "Epilogue", sans-serif;
  font-weight: 700;
  font-size: 56px;
  line-height: 64px;
  color: #000000;
}

.grid-container {
  display: grid;
  justify-content: center;
  grid-template-columns: 493px 493px 493px;
  /*Make the grid smaller than the container*/
  gap: 20px;
  /* background-color: #2196F3; */
  padding: 10px;
}

.grid-container > div {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
  height: 200px;
  border-radius: 16px;
}

.element {
  display: grid;
  justify-items: start;
}

.img-element {
  width: 30px;
  height: 30px;
  margin-top: 20px;
  margin-left: 39px;
  margin-bottom: 20px;
}

.text-large {
  font-family: "Epilogue", sans-serif;
  font-size: 24px;
  font-weight: 400;
  line-height: 24.6px;
  color: #333333;
  margin-left: 39px;
  margin-bottom: 10px;
}

.text-small {
  font-family: "Epilogue", sans-serif;
  font-size: 16px;
  font-weight: 400;
  line-height: 21px;
  color: #555555;
  margin-left: 37px;
  text-align: left;
  margin-right: 58px;
}
</style>
