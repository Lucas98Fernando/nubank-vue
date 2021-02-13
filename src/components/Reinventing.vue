<template>
  <section class="section" id="reinventing">
    <b-container align-v="center" fluid>
      <b-row align-v="center">
        <b-col lg="12">
          <h2>
            Reinventando <br />
            a relação das <br />
            pessoas com <br />
            o dinheiro.
          </h2>
          <a href="#"
            >É nisso que acreditamos
            <font-awesome-icon icon="arrow-right" class="arrow"
          /></a>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {
  name: 'Reinventing',
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/custom.scss";

#reinventing {
  background-image: url('../assets/images/bg-believe.webp');
  background-size: cover;
  background-position: center;
  padding: 10rem 5rem !important;

  h2 {
    color: $whiteSecondary !important;
  }

  a {
    color: $whiteSecondary !important;
  }
}
</style>
