<script setup lang="ts">
  import { RouterLink } from 'vue-router'
</script>

<style lang="scss" src="../styles/Header.scss"></style>

<template>
  <header>
    <h1 class="text-center pt-3">Vue Playground</h1>
    <div>
      <nav class="d-flex justify-content-center">
        <RouterLink to="/">Home</RouterLink>
        <span>/</span>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>
</template>
