<template>
  <section>
    <div class="client--info">
      <h6>¡Hola, Eduardo!</h6>
      <p>Documento de identidad</p>
      <p>Tipo de comisión</p>
      <p>E-mail</p>
      <p>CUSPP</p>
    </div>
    <div class="summary">
      <p>Tu fondo acumulado</p>
      <h4>S/ 0,000.00§</h4>
    </div>
  </section>
</template>

<style>
section {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin: 10px 25px 10px 10px;
}
.client--info p {
  margin: 0;
  padding: 0;
  font-size: 0.5rem;
}
.summary p {
  font-size: 0.625rem;
}
</style>
