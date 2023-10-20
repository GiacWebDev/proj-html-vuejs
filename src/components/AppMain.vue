<script>

import Portfolio from './partials/Portfolio.vue';
import PriceList from './partials/PriceList.vue';
import Blog from './partials/Blog.vue';
import Testimonial from './partials/Testimonial.vue';
import Partner from './partials/Partner.vue';

export default {
  name: 'AppMain',
  components: {
    Portfolio,
    PriceList,
    Blog,
    Testimonial,
    Partner,
  }
}
</script>


<template>


    <!-- bianca -->
  
  <div class="our-services py-5 text-center">

    <div class="container">

      <div class="row">
        <div class="col">
          <h5>Our Services</h5>
          <h3><strong>What</strong> we do</h3>
          <p>When, while the lovely valley teems with vapour oround meand the</p>
        </div>
      </div>
  
      <div class="row row-cols-4">
        
        <div class="col d-flex flex-column justify-content-center p-5">
          <div class="image d-flex align-items-center">
            <img src="/images/Group-247.png" alt="service">
          </div>
          <div class="info">
            <h4>data analysis</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur totam dolorem assumenda</p>
          </div>
        </div>
        
        <div class="col d-flex flex-column justify-content-center p-5">
          <div class="image d-flex align-items-center">
            <img src="/images/Group-567.png" alt="service">
          </div>
          <div class="info">
            <h4>data analysis</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur totam dolorem assumenda</p>
          </div>
        </div>
        
        <div class="col d-flex flex-column justify-content-center p-5">
          <div class="image d-flex align-items-center">
            <img src="/images/Group-538.png" alt="service">
          </div>
          <div class="info">
            <h4>data analysis</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur totam dolorem assumenda</p>
          </div>
        </div>
        
        <div class="col d-flex flex-column justify-content-center p-5">
          <div class="image d-flex align-items-center">
            <img src="/images/Group-566.png" alt="service">
          </div>
          <div class="info">
            <h4>data analysis</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur totam dolorem assumenda</p>
          </div>
        </div>
        
      
        
      </div>

      <button class="btns btn-orange">View All Services</button>
    </div>

  </div>

  <!-- blu -->
  <div class="Start-your-project py-5 white-text">
    <div class="container">
      <div class="row row-cols-2">
  
        <div class="col double-images">
          <img class="ps-5 pt-5 top" src="/images/men-data.png" alt="data">
          <img class="under" src="/images/nemoodar.png" alt="">
        </div>
  
        <div class="col info">          
          <h5>Start Your Project</h5>
          <h2><strong>Grow your business</strong>
          <br>
          with our strategy</h2>
          <p class="light-blue-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sunt debitis laborum quam magnam eius adipisci, assumenda officia voluptates maxime odit.assumenda officia voluptates</p>

          <div class="button-box d-flex justify-content-left">
            <button class="btns btn-orange me-3">try it now</button>
            <button class="btns btn-blue">explore more</button>
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
  <Blog />
  
  <!-- bianca -->
  <Testimonial />
  
  <!-- bianca -->
  <Partner />


</template>


<style lang="scss" scoped>
@use '../assets/scss/main.scss' as *;




.our-services {
  .container {
    align-items: center;
    .row {
      padding-top: 50px;
      .image {
        width: 150px;
        height: 150px;
        img {
          width: 100%;
        }
      }

      h4 {
        font-weight: 700;
        margin: 60px 0 20px 0;
      }
    }
  
  }
  
}


.Start-your-project {
  background-color: $light-primary;
  .double-images {
    position: relative;
    .under {
      position: absolute;
      left: 0;
    }
    img {
      width: 500px;
    }
  }
  .col.info {
    padding-top: 120px;
    h5 {
      color: $card-light;
    }
    p {
      width: 500px;
      margin: 0;
      margin: 30px 0;
    }

  }
}

</style>