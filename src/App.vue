<script setup lang="ts">
// On préfixe dans le cas ou le composant à le même nom qu'un élément HTML
import TheHeader from './components/Header.vue'
import Cart from './components/Cart/Cart.vue'
import Shop from './components/Shop/Shop.vue'
import TheFooter from './components/Footer.vue'
</script>

<template>
  <div class="app-container">
    <!-- en placant une classe sur le composant, elle vient directement se mettre sur le premier div du composant -->
    <TheHeader class="header b1" />
    <Shop class="shop b2" />
    <Cart class="cart b3" />
    <TheFooter class="footer b4" />
  </div>
</template>

<style lang="scss">
@import './assets/style/index.scss';
</style>
