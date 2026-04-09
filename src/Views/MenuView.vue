<script setup lang="ts"></script>

<template>
  <div class="app-container app-container-screen">
    <h1 class="app-title">MENU</h1>
    <h2 class="app-subtitle">Escolha uma opção para continuar</h2>

    <div class="app-form">
      <router-link to="/register" class="form-btn" tag="button">Registrar</router-link>
      <router-link to="/login" class="form-btn" tag="button">Entrar</router-link>
    </div>
  </div>
</template>

<style scoped></style>
