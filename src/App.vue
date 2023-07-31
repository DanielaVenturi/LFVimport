<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
   
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">LFV</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">        <RouterLink to="/">Home</RouterLink></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><RouterLink to="/carrinho">Carrinho</RouterLink></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><RouterLink to="/promocao">Promoção</RouterLink></a>
        </li>
      </ul>
    </div>
  </div>
</nav>


    <div class="wrapper">
      <nav>

        
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
