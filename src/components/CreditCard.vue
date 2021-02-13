<template>
    <section class="section" id="credit-card">
    <b-container align-v="center" fluid>
      <b-row align-v="center">
        <b-col lg="8">
            <a href="#" class="cta-credit-card">Cartão de crédito</a>
            <h2>Pode chamar ele de <br> roxinho. Além disso, <br> pode chamar ele de <br>
                moderno, gratuito e <br> prático também.</h2>
            <a href="#">Saiba mais
                <font-awesome-icon icon="arrow-right" class="arrow"/></a>
        </b-col>
        <b-col lg="4" class="col-card">
          <b-img
            class="card-nubank"
            src="../assets/images/card-nubank@3x.webp"
            fluid
          ></b-img>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {
  name: 'CreditCard',
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/custom.scss";

#credit-card {
    position: relative;

    .cta-credit-card {
        font-size: 3rem;
        font-weight: 500;
    }

    .col-card {
        position: absolute;
        right: 0;
        bottom: 0;
    }
    .card-nubank {
        width: 230px !important;
    }
}
</style>
