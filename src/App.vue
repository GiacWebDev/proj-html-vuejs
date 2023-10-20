<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import Chat from './components/partials/Chat.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    Chat
  }
}
</script>


<template>


  <AppHeader />
  <AppMain />
  <AppFooter />
  <Chat />


</template>


<style lang="scss">
@use './assets/scss/main.scss';



</style>