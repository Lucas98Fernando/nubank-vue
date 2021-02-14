<template>
  <section class="section" id="nu-conta">
    <b-container align-v="center" fluid>
      <b-row align-v="center">
        <b-col lg="5">
            <a href="#" class="cta-nu-conta">Conta do Nubank</a>
            <h2>Nossa conta digital <br> com mais de 20 <br> milhões de clientes <br>
                em todo o Brasil.</h2>
            <a href="#">Segura e sem complicações
                <font-awesome-icon icon="arrow-right" class="arrow"/></a>
        </b-col>
        <b-col lg="7" class="d-flex justify-content-end">
          <b-img
            class="phone-nu-conta"
            src="../assets/images/phone-nu-conta@0.5x.png"
            fluid
          ></b-img>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {
  name: 'NuConta',
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/custom.scss";

#nu-conta {
    background-color: rgb(245, 245, 245);

    .cta-nu-conta {
        font-size: 3rem;
        font-weight: 500;
    }

    .phone-nu-conta {
        width: 500px;
    }
}
</style>
