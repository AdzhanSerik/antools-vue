<template>
  <div class="px-20 pt-5">
    <Header :navigation="navigation" />
  </div>
</template>

<script setup>
import Header from "./components/Header.vue";

const navigation = [
  'Home',
  'Categories',
  'My Collections',
  'Blog',
]

localStorage.setItem('user', 'Atamchik')

</script>