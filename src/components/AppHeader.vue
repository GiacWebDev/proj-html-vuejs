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
  <header>

    <NavBar />
  
    <div class="jumbotron">
      <div class="container">
        <div class="row row-cols-2">
          
          <div class="col">
            info e buttons
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