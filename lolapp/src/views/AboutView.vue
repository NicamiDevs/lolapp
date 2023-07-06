<template>
  <div class="about bg-danger-subtle py-5 d-flex justify-content-around">
    <div class="w-50 ps-5">
      <h1>💻 Desarrolladores</h1>
      <h4>Proyecto realizado por Camilo Henao & Gonzalo Pua</h4>
      <p>Aplicación creada utilizando tecnologías como Vue JS, Bootstrap 5, TypeScript, etc, etc</p>
      
      <div class="d-flex w-50 justify-content-around">
        <div class="d-flex flex-column justify-content-around" style="height: 10rem;">
          <button type="button" class="btn btn-light d-flex py-2">
            <img src="../assets/images/linkedin.png" width="40" height="30" class="pe-2"/>
            Gonzalo Pua
          </button>
          <button type="button" class="btn btn-light d-flex py-2">
            <img src="../assets/images/github.png" width="40" height="30" class="pe-2"/>
            Gonzalo Pua
          </button>
        </div>

        <div class="d-flex flex-column justify-content-around" style="height: 10rem;">
          <button type="button" class="btn btn-light d-flex py-2">
            <img src="../assets/images/linkedin.png" width="40" height="30" class="pe-2"/>
            Camilo Henao
          </button>
          <button type="button" class="btn btn-light d-flex py-2">
            <img src="../assets/images/github.png" width="40" height="30" class="pe-2"/>
            Camilo Henao
          </button>
        </div>
      </div>
      <div class="d-flex justify-content-around mt-5">
        <img src="../assets/images/typescript.png" width="75" height="75" class="rounded shadow-lg"/>
        <img src="../assets/images/vuejs.png" width="75" height="75"/>
        <img src="../assets/images/bootstrap5.png" width="90" height="75"/>
      </div>
    </div>

    <div class="w-50" >
      <img src="../assets//images/developer.jpg" class="rounded shadow-lg" style="width: 90%; height: auto;"/>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    display: flex;
    align-items: center;
  }
}
</style>
