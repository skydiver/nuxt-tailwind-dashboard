<template>
  <div class="w-full md:w-1/2 xl:w-1/3 p-3">
    <Box title="Graph">
      <DoughnutChart :height="200" :options="options" :chartdata="chartdata" />
    </Box>
  </div>
</template>

<script>
import Box from '~/components/containers/Box.vue';
import DoughnutChart from '~/components/charts/DoughnutChart.vue';

export default {
  components: {
    Box,
    DoughnutChart
  },
  data() {
    return {
      options: {},
      chartdata: {
        labels: ['P1', 'P2', 'P3'],
        datasets: [
          {
            label: 'Issues',
            data: [300, 50, 100],
            backgroundColor: [
              'rgb(255, 99, 132)',
              'rgb(54, 162, 235)',
              'rgb(255, 205, 86)'
            ]
          }
        ]
      }
    };
  }
};
</script>

<style scoped></style>
