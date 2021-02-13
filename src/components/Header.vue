<template>
<section class="section" id="hero">
  <b-container  fluid>
    <b-row align-v="center">
      <b-col lg="4">
          <h1>Pix: um novo jeito de fazer transferências e pagamentos</h1>
          <a href="#">Saiba como funciona <font-awesome-icon icon="arrow-right" class="arrow"
        /></a>
      </b-col>
      <b-col lg="4">
          <b-img class="phone-header" fluid src="../assets/images/phone-header.webp" />
      </b-col>
      <b-col lg="4">
          <Form />
      </b-col>
    </b-row>
  </b-container>
</section>
</template>

<script>
import Form from './Form.vue';

export default {
  name: 'Header',
  components: {
    Form,
  },
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/custom.scss";

#hero {
    background-color: $primary;

    h1 {
        color: $whiteSecondary;
        font-weight: 600;
        font-size: 2.9rem;
        margin-bottom: 1rem;
    }

    a {
        color: $whiteSecondary;
        font-weight: 500;
        font-size: 1.12rem;
    }
}
</style>
