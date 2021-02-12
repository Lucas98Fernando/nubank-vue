<template>
  <div>
    <b-navbar toggleable="lg" type="light" variant="white">
      <b-navbar-brand href="#">
        <Logo />
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">Início</b-nav-item>
          <b-nav-item href="#">Conta digital</b-nav-item>
          <b-nav-item href="#">Cartão de crédito</b-nav-item>
          <b-nav-item href="#">Pix <b-badge>novo</b-badge></b-nav-item>
          <b-nav-item href="#">Empréstimo</b-nav-item>
          <b-nav-item href="#">Conta PJ</b-nav-item>
          <b-nav-item href="#">Rewards</b-nav-item>
          <b-nav-item href="#">Seguros <b-badge>novo</b-badge></b-nav-item>
          <b-nav-item href="#">Sobre nós</b-nav-item>
          <b-nav-item href="#">Carreiras</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Login</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
import Logo from './Logo.vue';

export default {
  name: 'Navbar',
  components: {
    Logo,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import '../assets/scss/variables.scss';

.navbar {
  padding: 0.6rem 2rem !important;

  .nav-link {
    font-size: 1.1rem;
    font-weight: 500;
    color: rgba(17, 17, 17, 0.7) !important;
    padding-right: 0.8rem !important;
    padding-left: 0.8rem !important;

    &:hover {
      color: $purpleLight !important;
    }

    .badge {
      border-radius: 20px;
      background-color: $whiteSecondary;
      color: $black;
      font-weight: 500;
      font-size: 1rem
    }
  }
}
@import 'node_modules/bootstrap/scss/bootstrap.scss';
</style>
