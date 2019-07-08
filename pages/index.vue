<template>
  <div id="main-container">
    <header>
      <div>
        <h6 class="title my-1">ESTADO DE CUENTA MENSUAL</h6>
        <h6 class="subtitle my-0">DE APORTES OBLIGATORIOS</h6>
        <p class="my-0">mes / año</p>
      </div>
      <logo />
    </header>
    <ClientInfo />
    <MonthlySummary />
    <TypeFund />
    <MonthlyMovemment />
    <ChartLine />
    <ChartBar />
    <Banner />
    <Footer />
    <header>
      <div>
        <h6 class="title my-1">ESTADO DE CUENTA MENSUAL</h6>
        <h6 class="subtitle my-0">ESTADO DE CUENTA MENSUAL</h6>
        <p class="my-0">mes / año</p>
      </div>
    </header>
    <TypeFund />
    <TypeFund />
    <VountaryFund />
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import ClientInfo from "~/components/Client-info.vue";
import MonthlySummary from "~/components/Monthly-summary.vue";
import TypeFund from "~/components/Type-fund.vue";
import MonthlyMovemment from "~/components/Monthly-movemment.vue";
import ChartLine from "~/components/Chart-line.vue";
import ChartBar from "~/components/Chart-bar.vue";
import Banner from "~/components/Banner.vue";
import Footer from "~/components/Footer.vue";
import VountaryFund from "~/components/Voluntary-fund.vue";

export default {
  components: {
    Logo,
    ClientInfo,
    MonthlySummary,
    TypeFund,
    MonthlyMovemment,
    ChartLine,
    ChartBar,
    Banner,
    Footer,
    VountaryFund
  }
};
</script>

<style>
#main-container {
  width: 70vw;
  margin: 0 auto;
}
@media (max-width: 600px) {
  #main-container {
    width: 100vw;
    margin: 0 auto;
  }
}
header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  background: #cf1b45;
  color: white;
  height: 5rem;
  padding: 10px;
}

.title {
  font-family: "Avenir", Arial, sans-serif;
  font-weight: bold;
}

.subtitle {
  font-weight: normal;
}

.links {
  padding-top: 15px;
}
</style>
