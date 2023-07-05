<script setup lang="ts">
import Carousel from "../components/Carousel/Carousel.vue"
</script>

<template>
  <main class="bg-primary-subtle w-100">
    <div class="d-flex flex-row justify-content-center py-5">
      <div class="shadow-lg w-50">
        <Carousel />
      </div>
    </div>

    <div class="d-flex flex-row justify-content-center pb-5">
      <select id="selector" class="form-select form-select-lg rounded">
          <option>- Server -</option>
          <option>LAS</option>
          <option>NA</option>
          <option>EUNE</option>
      </select>
      <div class="input-group w-50">
        <input type="search" class="form-control rounded" placeholder="Ingrese nombre de Invocador" aria-label="Search" aria-describedby="search-addon" />
        <button type="button" class="btn btn-outline-primary">Buscar</button>
      </div>
    </div>

    <div class="d-flex flex-column">
      <h1>AGREGAR MUCHAS COSAS MÁS</h1>
    </div>
  </main>
</template>

<style>
#selector{
  width: 10%;
}
</style>