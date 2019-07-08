<template>
  <div>
    <div class="statement">
      <i class="icon--check mx-1"></i>
      <h6 class="blue-color text-9 text-bold">
        Aportes obligatorios - marzo 2018 /
        <span class="text-grey text-8">Tipo de Fondo: 2</span>
      </h6>
    </div>
    <div class="card-container">
      <div class="card">
        <div class="cd-title text-8 my-1">Fondo anterior</div>
        <img class="mx-1 mb-3" src="~/assets/imgs/money-before.svg" width="35" alt="money" />
        <div class="cd-footer text-9">0000.00</div>
      </div>
      <h3 class="blue-color mx-3">+</h3>
      <div class="card">
        <div class="cd-title text-8 my-1">Aporte del mes</div>
        <img class="mx-1 mb-3" src="~/assets/imgs/contribute.svg" width="35" alt="money" />
        <div class="cd-footer text-9">0000.00</div>
      </div>
      <h3 class="blue-color mx-3">-</h3>
      <div class="card">
        <div class="cd-title text-8 my-1">Retiros y cargos</div>
        <img class="mx-1 mb-3" src="~/assets/imgs/withdraw.svg" width="35" alt="money" />
        <div class="cd-footer text-9">0000.00</div>
      </div>
      <h3 class="blue-color mx-3">+</h3>
      <div class="card">
        <p class="cd-title text-8 my-1">
          Rentabilidad
          acumulada
        </p>
        <img
          class="mx-1 mb-3"
          src="~/assets/imgs/acumulated-rentability.svg"
          width="30"
          alt="money"
        />
        <div class="cd-footer text-9">0000.00</div>
      </div>
      <h3 class="blue-color mx-3">=</h3>
      <div class="card">
        <p class="cd-title text-8 my-1">Fondo acumulado</p>
        <img class="mx-1 mb-3" src="~/assets/imgs/acumulated-money.svg" width="35" alt="money" />
        <div class="cd-footer text-9 dark">0000.00</div>
      </div>
    </div>
    <div class="text-center">
      <p class="text-8 mt-2 mb-0">El fondo acumulado para tu pensión de jubilación es de S/.00,000.</p>
      <p class="text-8 my-0">
        El cual está conformado por los aportes que realizaste a tu cuenta (S/.00,000) y
        la rentabilidad generada para ti (S/. 00,000).
      </p>
      <div class="conatiner-date my-3">
        <div class="statement mr-3">
          <i class="icon--arrow mx-1"></i>
          <h6 class="blue-color text-8">Fecha de afiliación a AFP Habitat: 00 / 00 / 0000</h6>
        </div>
        <div class="statement">
          <i class="icon--arrow mx-1"></i>
          <h6 class="blue-color text-8">Fecha en que llegó tu fondo a AFP Habitat: 00 / 00 / 0000</h6>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.card-container {
  display: flex;
  flex-direction: row;
  flex-flow: wrap;
  justify-content: center;
  margin: 0 1rem;
}
.card {
  border: 1px solid #5a9cbc;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.cd-title {
  color: #5a9cbc;
  min-width: 5.2rem;
}
.cd-footer {
  background: #5a9cbc;
  color: white;
  width: 100%;
  position: absolute;
  bottom: 0;
}
.cd-footer.dark {
  background: #18618f;
}

h3.mx-3 {
  display: flex;
  align-items: center;
}
.conatiner-date {
  display: flex;
  justify-content: center;
}
</style>
