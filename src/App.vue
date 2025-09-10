<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="container">
    <nav>
      <ul>
        <li>
          <strong>Pico Components</strong>
        </li>
      </ul>
      <ul>
        <li><RouterLink to="/">Home</RouterLink></li>
        <li><RouterLink to="/stuff">Stuff</RouterLink></li>
      </ul>
    </nav>
  </header>

  <RouterView />
</template>

<style>
nav {
  justify-content: space-between;
}
</style>
