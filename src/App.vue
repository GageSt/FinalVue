<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <body>
  <header class="header">

    <nav>
      <a href="#nameBox">>Beginning</a>
      <a href="#card">>Summary</a>
      <a href="#terminalCommands">>Terminal Commands</a>
      <a href="#conversions">>JS to JSX</a>
    </nav>
    <div class="logoName">
      <h1>Note<br />Book +</h1>
    </div>

  </header>

  <RouterView />

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.2/font/bootstrap-icons.min.css" />
  <footer>
    <h4>2023 | Gage Tranter</h4>
    <div class="footerLinks">
      <a class="btn btn-outline btn-floating m-1" href="#" role="button">
        <i class="bi bi-envelope-at-fill text-light"></i>
      </a>

      <a class="btn btn-outline btn-floating m-1" href="#" role="button">
        <i class="bi bi-google text-light"></i>
      </a>

      <a class="btn btn-outline btn-floating m-1" href="#" role="button">
        <i class="bi bi-github text-light"></i>
      </a>
    </div>
    <h4>SWDV-143</h4>
  </footer>
</body>
</template>

<style scoped></style>
