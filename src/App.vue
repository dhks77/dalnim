<template>
  <b-container>
    <gnb />
    <router-view></router-view>
    <test />
  </b-container>
</template>

<script>
import Gnb from './components/gnb/Gnb.vue';
import Test from './components/footer/Footer.vue';

export default {
  components: {
    Gnb,
    Test,
  },
};
</script>
