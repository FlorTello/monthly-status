
<script>
import { Line } from "vue-chartjs";

export default {
  extends: Line,
  data: () => ({
    chartdata: {
      labels: [
        "ENE",
        "FEB",
        "MAR",
        "ABR",
        "MAY",
        "JUN",
        "JUL",
        "AGO",
        "SET",
        "OCT",
        "NOV",
        "DIC"
      ],
      datasets: [
        {
          label: "Data One",
          backgroundColor: "#f87979",
          data: [300, 800, 600, 1000, 800, 600, 1000, 600, 1000]
        }
      ]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false
    }
  }),

  mounted() {
    this.renderChart(this.chartdata, this.options);
  }
};
</script>