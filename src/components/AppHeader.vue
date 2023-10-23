<script>

import NavBar from './partials/NavBar.vue';
import { mainMenu } from '../data/store';

export default {
  name: 'AppHeader',
  components: {
    NavBar
  },
  data() {
    return {
      mainMenu,
      menuItemSelected: ''
    }
  } 
}
</script>


<template>
  <header class="white-text">

    <NavBar :mainMenu="mainMenu" :menuItemSelected="menuItemSelected"/>
  
    <div class="jumbotron">
      <div class="container">
        <div class="row row-cols-2">
          
          <div class="col">
            <h1><strong>business planning</strong>
            <br>digital tecnology
            <br>
            <strong>modern solution!</strong></h1>

            <p class="light-blue-text">When, while the vovely valley teems with vapour around meand the meridian sun strikes the upper surface.</p>

            <div class="button-box d-flex justify-content-left">
              <button class="btns btn-orange me-3">try it now</button>
              <button class="btns btn-blue">explore more</button>
            </div>
          </div>
  
          <div class="col">
           <img src="/images/header.png" alt="header">
          </div>
  
        </div>
      </div>
    </div>

  </header>


</template>


<style lang="scss" scoped>
@use '../assets/scss/main.scss' as *;

 header {
  z-index: 999!important;
  background-color: $light-primary;
  padding-bottom: 100px;
  .jumbotron {
    padding-top: 90px;
    .col {
      margin: 0;
      h1 {
        padding-top: 80px;
        line-height: 3rem;
      }
      padding: 0;
      p {
        width: 400px;
        margin: 0;
        padding: 20px 0 30px 0;
      }
      img {
        width: 600px;
      }
    }
  }
}

</style>