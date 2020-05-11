<template>
  <div id="app" style="width:800px; overflow-x: auto;">
    <highcharts-demo></highcharts-demo>
  </div>
</template>

<script>
import HighchartsDemo from "./components/HighchartsDemo";

export default {
  name: "App",
  components: {
    HighchartsDemo
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
</style>
