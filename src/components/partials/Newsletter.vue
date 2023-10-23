
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

      <div class="col-4">
        <div class="box-input">
          <input type="text" placeholder="Enter Your Email Adress">
          <button class="btns btn-blue">subscribe</button>
        </div>
      </div>
    
    </div>
  </div>
  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

.newsletter {
  border-radius: 20px;
  color: $card-light;
  .row {
    padding: 50px 20px;
    .box-input {
      background-color: white;
      border-radius: 50px;
      padding: 3px 3px 3px 20px;
      input {
        border: none;
        margin-right: 98px;
      }
    }
    p {
      color: $card-light;
    }
  }
  
}

</style>