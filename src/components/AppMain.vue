<script>

import Portfolio from './partials/Portfolio.vue';
import PriceList from './partials/PriceList.vue';

export default {
  name: 'AppMain',
  components: {
    Portfolio,
    PriceList
  }
}
</script>


<template>


    <!-- bianca -->
  
  <div class="Our-services py-5 text-center">

    <div class="container">

      <div class="row">
        <div class="col">
          <h5>Our Services</h5>
          <h3><strong>What</strong> we do</h3>
          <p>When, while the lovely valley teems with vapour oround meand the</p>
        </div>
      </div>
  
      <div class="row row-cols-4 debug">
        <div class="col d-flex flex-column justify-content-center">
          immagine
          <h4>titolo</h4>
          <p>testo</p>
        </div>
        <div class="col d-flex flex-column justify-content-center">
          immagine
          <h4>titolo</h4>
          <p>testo</p>
        </div>
        <div class="col d-flex flex-column justify-content-center">
          immagine
          <h4>titolo</h4>
          <p>testo</p>
        </div>
        <div class="col d-flex flex-column justify-content-center">
          immagine
          <h4>titolo</h4>
          <p>testo</p>
        </div>
      </div>

      <button class="btns">View All Services</button>
    </div>

  </div>

    
  <!-- blu -->
  <div class="Start-your-project py-5 white-text">
    <div class="container">
      <div class="row row-cols-2">
  
        <div class="col">
          immagine sopra un altra immagine
        </div>
  
        <div class="col">          
          <h5>Start Your Project</h5>
          <h2><strong>Grow your business</strong>with our strategy</h2>
          <p class="light-blue-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sunt debitis laborum quam magnam eius adipisci, assumenda officia voluptates maxime odit.assumenda officia voluptates</p>

          <div class="button-box d-flex justify-content-left">
              <button class="btns me-3">try it now</button>
              <button class="btns">explore more</button>
            </div>
        </div>
      </div>
    </div>
  </div>
    
    <!-- bianca -->
  <Portfolio />
  
  <!-- blu -->
  <PriceList />
  
  <!-- bianca -->
  <div class="Blog"></div>
  
  <!-- bianca -->
  <div class="Testimonials"></div>
  
  <!-- bianca -->
  <div class="Sponsors"></div>



</template>


<style lang="scss" scoped>
@use '../assets/scss/main.scss' as *;

.container {
  height: 600px;
}

.Start-your-project {
  background-color: $light-primary;
}

</style>