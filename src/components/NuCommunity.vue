<template>
  <section class="section" id="nu-community">
    <b-container align-v="center" fluid>
      <b-row align-v="center">
        <b-col lg="12">
          <h2>NuCommunity</h2>
          <h2>
            A comunidade <br />
            oficial do Nubank. <br />
          </h2>
          <a href="#"
            >Tire dúvidas, compartilhe ideias e faça parte
            <font-awesome-icon icon="arrow-right" class="arrow rotate"
          /></a>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {
  name: 'NuCommunity',
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/custom.scss";

#nu-community {
  background-image: url("../assets/images/bg-nu-community.webp");
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
