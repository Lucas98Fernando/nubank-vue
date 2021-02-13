<template>
<section class="section" id="benefits">
  <b-container>
    <b-row align-v="center">
      <b-col lg="7">
          <h2>Traga seu FGTS e Auxílio Emergencial para o Nubank</h2>
           <a href="#">Confira os benefícios <font-awesome-icon icon="arrow-right" class="arrow"
        /></a>
      </b-col>
      <b-col lg="5">
          <b-img class="girl-benefits" src="../assets/images/girl-benefits.webp" fluid></b-img>
      </b-col>
    </b-row>
  </b-container>
</section>
</template>

<script>
export default {
  name: 'Benefits',
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/custom.scss";

#benefits {
    padding: 4rem 5rem;
    min-height: 100vh;

    h2 {
        color: $black;
        font-weight: 500;
        font-size: 2.9rem;
        margin-bottom: 1rem;
        padding-right: 19rem;
        padding-bottom: 1rem;
    }

    a {
        color: $primary;
        font-weight: 500;
        font-size: 1.12rem;
    }

    .girl-benefits {
        max-width: 400px;
    }
}
</style>
