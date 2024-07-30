
<template>
   <div id="app">
    <Promo />
    <Navbar />
    <British />
    <Cards />
    <Footer />
    <RouterView />
  </div>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
import British from './components/British.vue';
import Promo from './components/Promo.vue';
import Cards from './components/Cards.vue';
</script>

<style scoped>

</style>

