<script>
import AppHeader from './components/Header/AppHeader.vue';
import AppMain from './components/Main/AppMain.vue';
import AppFooter from './components/Footer/AppFooter.vue';

export default {
  name: "App",
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
};

</script>

<template>

  <div class="container">
    <AppHeader />

    <AppMain />

    <AppFooter />
  </div>

</template>

<style lang="scss">
@use "./styles/main";

.container {
  width: 80vw;
  margin: 0 auto;
  background-color: aquamarine;
}
</style>
