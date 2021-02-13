<template>
  <footer id="footer">
    <b-container align-v="center" align-h="center" fluid>
      <b-row align-v="top">
        <b-col lg="3">
          <ul>
            <li><p class="title-itens">Nubank</p></li>
            <li><a href="#" class="item-footer">Sobre nós</a></li>
            <li><a href="#" class="item-footer">Carreiras</a></li>
            <li><a href="#" class="item-footer">Perguntas frequentes</a></li>
            <li><a href="#" class="item-footer">Contato</a></li>
            <li><a href="#" class="item-footer">Impresa</a></li>
          </ul>
        </b-col>
        <b-col lg="3">
          <ul>
            <li><p class="title-itens">Produtos</p></li>
            <li><a href="#" class="item-footer">Conta digital</a></li>
            <li><a href="#" class="item-footer">Cartão de crédito</a></li>
            <li><a href="#" class="item-footer">Rewards</a></li>
            <li><a href="#" class="item-footer">Empréstimo</a></li>
            <li><a href="#" class="item-footer">Conta PJ</a></li>
          </ul>
        </b-col>
        <b-col lg="3">
          <ul>
            <li><p class="title-itens">Explore</p></li>
            <li>
              <a href="#" class="item-footer"
                >Comunidade
                <font-awesome-icon icon="arrow-right" class="arrow rotate"
              /></a>
            </li>
            <li>
              <a href="#" class="item-footer"
                >Blog
                <font-awesome-icon icon="arrow-right" class="arrow rotate"
              /></a>
            </li>
            <li>
              <a href="#" class="item-footer"
                >Newsletter
                <font-awesome-icon icon="arrow-right" class="arrow rotate"
              /></a>
            </li>
            <li>
              <a href="#" class="item-footer"
                >México
                <font-awesome-icon icon="arrow-right" class="arrow rotate"
              /></a>
            </li>
            <li>
              <a href="#" class="item-footer"
                >Argentina
                <font-awesome-icon icon="arrow-right" class="arrow rotate"
              /></a>
            </li>
            <li>
              <a href="#" class="item-footer"
                >Colômbia
                <font-awesome-icon icon="arrow-right" class="arrow rotate"
              /></a>
            </li>
          </ul>
        </b-col>
        <b-col lg="3">
          <ul>
            <li><p class="title-itens">Veja também</p></li>
            <li>
              <a href="#" class="item-footer"
                >Auxílio emergencial e FGTS
                <font-awesome-icon icon="arrow-right" class="arrow"
              /></a>
            </li>
            <li>
              <a href="#" class="item-footer"
                >Tudo sobre Pix
                <font-awesome-icon icon="arrow-right" class="arrow"
              /></a>
            </li>
          </ul>
        </b-col>
      </b-row>
      <b-row align-v="top">
        <b-col lg="3">
          <ul>
            <li><p class="title-itens">Transparência</p></li>
            <li><a href="#" class="item-footer">Política de Privacidade</a></li>
            <li><a href="#" class="item-footer">Política de Complience</a></li>
            <li><a href="#" class="item-footer">Contratos</a></li>
            <li><a href="#" class="item-footer">Política de Segurança</a></li>
            <li><a href="#" class="item-footer">Relatórios Financeiros</a></li>
            <li><a href="#" class="item-footer">Ética & Complience</a></li>
            <li><a href="#" class="item-footer">Dados Abertos</a></li>
            <li><a href="#" class="item-footer">SCR</a></li>
          </ul>
        </b-col>
        <b-col lg="3">
          <ul>
            <li><p class="title-itens">Ouvidoria</p></li>
            <li><a href="#" class="item-footer">0800 887 0463</a></li>
            <li><a href="#" class="item-footer">ouvidoria@nubank.com.br</a></li>
            <li>
              <a href="#" class="item-footer"
                >Atendimento das 9hrs às 18h (dias úteis)</a
              >
            </li>
          </ul>
        </b-col>
        <b-col lg="3">
          <ul>
            <li><p class="title-itens">Fale com a gente</p></li>
            <li><a href="#" class="item-footer">0800 608 6236</a></li>
            <li><a href="#" class="item-footer">meajuda@nubank.com.br</a></li>
            <li><a href="#" class="item-footer">Atendimento 24h</a></li>
          </ul>
        </b-col>
        <b-col lg="3">
          <ul>
            <li><p class="title-itens">Baixe o app</p></li>
            <li>
              <a href="#" class="item-footer icon"><AppleStore /></a>
            </li>
            <li>
              <a href="#" class="item-footer icon"><GooglePlay /></a>
            </li>
          </ul>
        </b-col>
      </b-row>
      <hr />
      <b-row align-v="top" class="mt-5 pt-5 d-flex align-items-center">
        <b-col lg="6" class="d-flex">
          <div>
            <LogoWhite />
          </div>
          <div class="d-flex flex-column ml-4">
            <span class="item-footer copy"
              >&copy; 2021 Nu Pagamentos S.A. 18.236.120/0001-58</span
            >
            <span class="item-footer copy"
              >Rua Capote Valente, 39 - São Paulo, SP - 05409-000</span
            >
          </div>
        </b-col>
        <b-col lg="6">
          <div class="social-icons d-flex justify-content-end">
            <a href="#"><Facebook /></a>
            <a href="#"><Instagram /></a>
            <a href="#"><Linkedin /></a>
            <a href="#"><YouTube /></a>
            <a href="#"><Twitter /></a>
          </div>
        </b-col>
      </b-row>
      <hr />
      <b-row class="lang">
        <b-col lg="12" class="d-flex justify-content-end mt-5">
          <b-form-group>
            <b-form-radio-group
              id="radio-group-1"
              v-model="selected"
              :options="options"
            ></b-form-radio-group>
          </b-form-group>

          <b-form-group>
            <b-form-radio-group
              id="radio-group-2"
              v-model="selected"
            >
              <b-form-radio value="first" class="switch-lang"
                >Português</b-form-radio
              >
              <b-form-radio value="second" class="switch-lang"
                >English</b-form-radio
              >
            </b-form-radio-group>
          </b-form-group>

        </b-col>
      </b-row>
    </b-container>
  </footer>
</template>

<script>
import AppleStore from '@/components/AppleStore.vue';
import GooglePlay from '@/components/GooglePlay.vue';
import LogoWhite from '@/components/LogoWhite.vue';
import Facebook from '@/components/Social/Facebook.vue';
import Instagram from '@/components/Social/Instagram.vue';
import Linkedin from '@/components/Social/Linkedin.vue';
import YouTube from '@/components/Social/YouTube.vue';
import Twitter from '@/components/Social/Twitter.vue';

export default {
  name: 'Footer',
  components: {
    AppleStore,
    GooglePlay,
    LogoWhite,
    Facebook,
    Instagram,
    Linkedin,
    YouTube,
    Twitter,
  },
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/custom.scss";

#footer {
  padding: 5rem 1rem !important;
  background: $black;

  .container-fluid {
    .row {
      margin-bottom: 5rem;

      &.lang {
          margin-bottom: 0;
      }

      .switch-lang {
          color: $whiteSecondary;
      }
    }
  }

  ul {
    list-style: none;
    padding-left: 0;
  }

  .title-itens {
    color: $whiteSecondary;
    margin-bottom: 1.8rem;
    font-weight: 400 !important;
  }

  .item-footer {
    color: $whiteSecondary;
    line-height: 2rem;

    &:hover {
      color: $purpleLight;
      text-decoration: none;
    }

    &.copy {
      line-height: 1.5rem;
    }
  }
}
</style>
