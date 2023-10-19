<script>

import NavBar from './partials/NavBar.vue'; 

export default {
  name: 'AppHeader',
  components: {
    NavBar
  }
}
</script>


<template>
  <header class="white-text">

    <NavBar />
  
    <div class="jumbotron">
      <div class="container">
        <div class="row row-cols-2">
          
          <div class="col">
            <h1><strong>business planning</strong></h1>
            <h1>digital tecnology</h1>
            <h1><strong>modern solution!</strong></h1>

            <p class="light-blue-text">When, while the vovely valley teems with vapour around meand the meridian sun strikes the upper surface.</p>

            <div class="button-box d-flex justify-content-left">
              <button class="btns me-3">try it now</button>
              <button class="btns">explore more</button>
            </div>
          </div>
  
          <div class="col">
           immagine
          </div>
  
        </div>
      </div>
    </div>

  </header>


</template>


<style lang="scss" scoped>
@use '../assets/scss/main.scss' as *;

 header {
  background-color: $light-primary;
  .jumbotron {
    height: 500px;
  }
}

</style>