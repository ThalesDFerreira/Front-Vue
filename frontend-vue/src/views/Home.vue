<template>
  <Banner />
  <div class="main-container">
    <h1>Monte o seu burger:</h1>
    <BurgerForm />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue';
import BurgerForm from '../../../backend-vue/BurgerForm.vue';

export default {
  name: 'Home',
  components: {
    Banner,
    BurgerForm,
  },
};
</script>
