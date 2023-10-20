
<script>
export default {
  name: 'Newsletter'  
}
</script>


<template>
  
  <div class="newsletter container btn-orange">
    <div class="row d-flex align-items-center">
      <div class="col-8">
        <h2><strong>we offer awesome services</strong></h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit, magni.</p>
      </div>

      <div class="col-4 debug">
        <div class="box-input debug">
          <input type="text" placeholder="Enter Your Email Adress">
          <button class="btns">subscribe</button>
        </div>
      </div>
    
    </div>
  </div>
  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

.newsletter {
  border-radius: 20px;
  padding: 50px 30px;
  color: $card-light;
  box-input {
    background-color: $card-light;
  }
}

</style>