<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <Navbar />
    <Header />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue';
import Header from '@/components/Header.vue';

export default {
  name: 'Home',
  components: {
    Navbar,
    Header,
  },
};
</script>
