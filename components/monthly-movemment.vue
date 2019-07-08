<template>
  <div>
    <div id="monthy-section">
      <div class="mx-2 left">
        <div class="statement">
          <i class="icon--check mr-2"></i>
          <h6 class="blue-color text-8">Movimiento del mes</h6>
        </div>
        <p class="text-8">1. Aportes Obligatorios del 01/08/2017 al 31/08/2017</p>
        <table class="table table-bordered">
          <thead class="theader">
            <tr>
              <th rowspan="2">Tipo de Movimiento</th>
              <th rowspan="2">Mes</th>
              <th rowspan="2">Fecha</th>
              <th rowspan="2">Cuenta personal S/.</th>
              <td colspan="2">Comisión S/.*.</td>
              <td rowspan="2">Seguro S/.</td>
            </tr>
            <tr>
              <th>sobre sueldo</th>
              <td>sobre fondo</td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="right">
        <div class="statement">
          <i class="icon--check mr-2"></i>
          <h6 class="blue-color text-8">Bonos</h6>
        </div>
        <p class="text-8">2. Bono de Reconocimiento</p>
        <img class="mx-1 mb-3" src="../assets/imgs/money.svg" width="30" alt="money" />
        <p class="text-6">
          La situación actual de tu Bono de Reconocimiento es: _____________________,
          su Valor Nominal es: S/ _____________ y el Último Valor Reconocido por la ONP es: S/ _____________
        </p>
        <p class="text-5">
          Si cuentas con trámite de bono y deseas actualizar tus datos, acércate a nuestras
          agencias a fin de suscribir el formato de actualización de datos personales para la ONP.
        </p>
      </div>
    </div>
    <div class="conatiner-date my-3">
      <div class="statement mr-3">
        <i class="icon--arrow mx-1"></i>
        <h6 class="blue-color text-8">Rentabilidad del mes: S/ 00.00</h6>
      </div>
      <div class="statement mr-3">
        <i class="icon--arrow mx-1"></i>
        <h6 class="blue-color text-8">Rentabilidad Acumulada: S/ 00.00</h6>
      </div>
      <div class="statement">
        <i class="icon--arrow mx-1"></i>
        <h6 class="blue-color text-8">Rentabilidad del SPP: S/ 00.00</h6>
      </div>
    </div>
  </div>
</template>

<style>
#monthy-section {
  display: flex;
  flex-direction: row;
}
.left {
  width: 65%;
}
.right {
  width: 35%;
}
.theader {
  background: #5a9cbc;
  color: white;
}
.table th,
.table td {
  font-size: 7px;
  margin: 0;
  padding: 0.3rem;
}
</style>
