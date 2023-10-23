
<script>
export default {
  name: 'Testimonial'
}
</script>


<template>

  <div class="testimonial py-5">
    <div class="container">
      <div class="row row-cols-5 ">
        
        <div class="col debug d-flex justify-content-center">
          <img src="/images/client-1-1.png" alt="">
        </div>

        <div class="col debug d-flex justify-content-centern">
          <img src="/images/clienty-2.png" alt="" class="_height">
        </div>

        <div class="col debug d-flex justify-content-center">
          <img src="/images/clienty-4.png" alt="">
        </div>

        <div class="col debug d-flex justify-content-center">
          <img src="/images/client-5.png" alt="">
        </div>

        <div class="col debug d-flex justify-content-center">
          <img src="/images/clienty-3.png" alt="">
        </div>

        
      </div>
    </div>
  </div>
  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

.testimonial {
  margin: 60px 0;
  .col {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  img {
    width: 50%;
    height: 70%;
  }
  img._height {
    width: 50%;
    height: 50%;
  }
}

</style>