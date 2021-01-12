<template>
  <div>
    <h1>Chart.js</h1>
    <BarChart :propsdata="chartDataSet"></BarChart>
    <LineChart></LineChart>
  </div>
</template>

<script>
import BarChart from './components/BarChart.vue';
import LineChart from './components/LineChart.vue';

export default {
  components: {
    BarChart,
    LineChart,
  },
  data() {
    return {
      chartDataSet: [12, 19, 3, 5, 2, 3],
    }
  },
}
</script>

<style>

</style>