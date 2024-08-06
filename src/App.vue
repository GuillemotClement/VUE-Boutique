<script setup lang="ts">
// On préfixe dans le cas ou le composant à le même nom qu'un élément HTML
import TheHeader from './components/AppHeader.vue'
import Cart from './components/AppCart.vue'
import Shop from './components/AppShop.vue'
import TheFooter from './components/AppFooter.vue'
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
