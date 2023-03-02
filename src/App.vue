<template>
  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
    <RouterLink to="/blog">Blog</RouterLink>
    <RouterLink to="/get-a-quote">Get A Quote</RouterLink>
    <RouterLink to="/media">Media</RouterLink>
    <RouterLink to="/shop">Shop</RouterLink>
  </nav>

  <RouterView />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>
