<template>
  <nav>
    <RouterLink class="btn mx-2" to="/">Home</RouterLink>
    <RouterLink class="btn mx-2" to="/about">About</RouterLink>
    <RouterLink class="btn mx-2" to="/blog">Blog</RouterLink>
    <RouterLink class="btn mx-2" to="/get-a-quote">Get A Quote</RouterLink>
    <RouterLink class="btn mx-2" to="/media">Media</RouterLink>
    <RouterLink class="btn mx-2" to="/shop">Shop</RouterLink>
  </nav>

  <RouterView />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<style lang="scss">
@import 'bootstrap/scss/bootstrap.scss';
</style>
