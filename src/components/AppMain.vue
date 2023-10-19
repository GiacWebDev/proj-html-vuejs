<script>
export default {
  name: 'AppMain'
}
</script>


<template>

  <div class="container text-center py-5">
    <!-- bianca -->
    <div class="Our-services">
      <p>Our Services</p>
      <h2><strong>What</strong>we do</h2>
      <p>When, while the lovely valley teems with vapour oround meand the</p>

      <div class="row row-cols-4 my-4 debug">
        <div class="col d-flex flex-column justify-content-center">
          immagine
          <h3>titolo</h3>
          <p>testo</p>
        </div>
        <div class="col d-flex flex-column justify-content-center">
          immagine
          <h3>titolo</h3>
          <p>testo</p>
        </div>
        <div class="col d-flex flex-column justify-content-center">
          immagine
          <h3>titolo</h3>
          <p>testo</p>
        </div>
        <div class="col d-flex flex-column justify-content-center">
          immagine
          <h3>titolo</h3>
          <p>testo</p>
        </div>
      </div>

      <button class="btns">View All Services</button>
    </div>
    
    <!-- blu -->
    <div class="Start-your-yrojecy"></div>
    
    <!-- bianca -->
    <div class="Portfolio"></div>
    
    <!-- blu -->
    <div class="Price-list"></div>
    
    <!-- bianca -->
    <div class="Blog"></div>
    
    <!-- bianca -->
    <div class="Testimonials"></div>
    
    <!-- bianca -->
    <div class="Sponsors"></div>
  </div>



</template>


<style lang="scss" scoped>
@use '../assets/scss/main.scss' as *;

.Our-services .row .col {
  height: 300px;
}

</style>