<template>
  <img id="logo" alt="TimaTech Logo" src="./assets/TimCanDo_logo.jpeg" />
  <TimaTech msg="Tim Can't Do Handyman Services" />
</template>

<script>
import TimaTech from "./components/TimaTech.vue";

export default {
  name: "App",
  components: {
    TimaTech,
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
}

#logo {
  border-radius: 25px;
  filter: drop-shadow(0 0 0.2rem gray);
}
</style>
