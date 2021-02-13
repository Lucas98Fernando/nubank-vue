<template>
  <section class="section" id="rewards">
    <b-container align-v="center" fluid>
      <b-row align-v="center">
        <b-col lg="8">
          <a href="#" class="cta-rewards">Rewards</a>
          <h2>
            Um programa de <br />
            pontos justo e fácil <br />
            de usar.
          </h2>
          <a href="#" id="know-more"
            >Saiba mais <font-awesome-icon icon="arrow-right" class="arrow"
          /></a>
        </b-col>
        <b-col lg="4" class="col-card">
          <b-img
            class="card-rewards"
            src="../assets/images/rewards@3x.webp"
            fluid
          ></b-img>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {
  name: 'Rewards',
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/custom.scss";

#rewards {
    background-color: rgb(83, 0, 130);

    h2 {
        color: $whiteSecondary !important;
    }

    a {
        color: $whiteSecondary !important;
    }

    .cta-rewards {
        font-size: 3rem;
        font-weight: 500;
        color: rgb(192, 147, 251) !important;
    }

    .arrow {
        transform: rotateZ(-45deg);
    }
}

</style>
