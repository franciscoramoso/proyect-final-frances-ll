<template>
  <div>
    <b-navbar type="dark" variant="dark">
      <b-navbar-nav>
        <b-navbar-brand href="/">Casa Pinolo <small>By Paco</small></b-navbar-brand>

        <b-nav-item href="/">D'accueil</b-nav-item>

        <b-button variant="danger" href="/platillo" v-b-tooltip.hover title="Le meilleur plat!">PLAT SPÉCIAL!</b-button>

        <b-nav-item href="/carta">Menu</b-nav-item>

        <b-nav-item href="/contactanos">Contactez nous</b-nav-item>

        <b-nav-item href="/acerca">Près de nous</b-nav-item>

      </b-navbar-nav>
    </b-navbar>
  </div>
</template>

<script></script>

<style scoped lang="scss">
  small{
    font-size: x-small;
  }
</style>
