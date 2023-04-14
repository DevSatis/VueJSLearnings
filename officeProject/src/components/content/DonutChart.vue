<template>
      <div class="col-md-2" style="background-color: white;">
        <h4 style="border-bottom: 1px solid #eee;"> Donut Chart</h4>
        <canvas id="donutChart" height="400" ></canvas>
      </div>
</template>
<script>
import Chart from 'chart.js/auto'
export default {
  name: "DonutChart",
  mounted() {
    console.log("Mounted !");

    const ctx = document.getElementById('donutChart');

    const donutChart = new Chart(ctx, {
      type: 'doughnut',
      data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
          label: '# of Votes',
          data: [12, 19, 3, 5, 2, 3],
          backgroundColor: [
            'rgba(255, 99, 132, 0.2)',
            'rgba(54, 162, 235, 0.2)',
            'rgba(255, 206, 86, 0.2)',
            'rgba(75, 192, 192, 0.2)',
            'rgba(153, 102, 255, 0.2)',
            'rgba(255, 159, 64, 0.2)'
          ],
          borderColor: [
            'rgba(255, 99, 132, 1)',
            'rgba(54, 162, 235, 1)',
            'rgba(255, 206, 86, 1)',
            'rgba(75, 192, 192, 1)',
            'rgba(153, 102, 255, 1)',
            'rgba(255, 159, 64, 1)'
          ],
          borderWidth: 1
        }]
      },
      options: {
        scales: {
          y: {
            beginAtZero: true
          }
        }
      }
    });
    donutChart;
  }

}


</script>
<style scoped></style>