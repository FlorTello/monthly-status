
<script>
import { Bar } from "vue-chartjs";

export default {
  extends: Bar,
  data: () => ({
    chartdata: {
      labels: ["Habitat", "Integra", "Profuturo", "Prima", "Promedio del SPP"],
      datasets: [
        {
          label: "Data One",
          backgroundColor: "#f87979",
          data: [90, 60, 50, 60, 90]
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