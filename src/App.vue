<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

import { QuickLinks } from './data/store';
import { Resources } from './data/store';
import { Contacts } from './data/store';



export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },

  data() {
    return {      
      QuickLinks,
      Resources,
      Contacts
    }
  }
}
</script>


<template>


  <AppHeader />
  <AppMain />
  <AppFooter :QuickLinks="QuickLinks" :Resources="Resources" :Contacts="Contacts" />


</template>


<style lang="scss">
@use './assets/scss/main.scss';



</style>