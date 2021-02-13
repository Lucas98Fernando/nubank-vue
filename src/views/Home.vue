<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <Navbar />
    <Header />
    <Benefits />
    <NuConta />
    <CreditCard />
    <Rewards />
    <Reinventing />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue';
import Header from '@/components/Header.vue';
import Benefits from '@/components/Benefits.vue';
import NuConta from '@/components/NuConta.vue';
import CreditCard from '@/components/CreditCard.vue';
import Rewards from '@/components/Rewards.vue';
import Reinventing from '@/components/Reinventing.vue';

export default {
  name: 'Home',
  components: {
    Navbar,
    Header,
    Benefits,
    NuConta,
    CreditCard,
    Rewards,
    Reinventing,
  },
};
</script>
