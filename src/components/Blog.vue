<template>
  <section class="section" id="blog">
    <b-container align-v="center" fluid>
      <b-row align-v="center">
        <b-col lg="12">
          <h2>
            Um blog para você <br />
            repensar o seu <br />
            dinheiro.
          </h2>
          <a href="#"
            >Conheça o fala, Nubank
            <font-awesome-icon icon="arrow-right" class="arrow rotate"
          /></a>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {
  name: 'Blog',
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/custom.scss";

#blog {
  background-image: url("../assets/images/bg-blog.webp");
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
