<script setup lang="ts">
// On préfixe dans le cas ou le composant à le même nom qu'un élément HTML
import TheHeader from './components/Header.vue'
import Cart from './components/Cart.vue'
import Shop from './components/Shop.vue'
import TheFooter from './components/Footer.vue'
</script>

<template>
  <TheHeader />
  <Shop />
  <Cart />
  <TheFooter />
</template>

<style lang="scss">
@import './assets/style/index.scss';
</style>
