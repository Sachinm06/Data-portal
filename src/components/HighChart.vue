<template>
    <div>
      <div id="chart-container"></div>
    </div>
  </template>
  
  <script>
  export default {
    mounted() {
      // Ensure Highcharts is available globally
      const Highcharts = require('highcharts');
      require('highcharts/modules/exporting')(Highcharts);
  
      // Then, create your chart
      Highcharts.chart('chart-container', {
        chart: {
          type: 'bar'
        },
        title: {
          text: 'Sample Chart'
        },
        series: [{
          name: 'Data',
          data: [1, 2, 3, 4, 5]
        }]
      });
    }
  }
  </script>
  