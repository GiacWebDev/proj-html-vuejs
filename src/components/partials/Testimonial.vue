<script>
export default {
    name: 'Testimonial'
}
</script>


<template>

  <div class="testimonial my-5 text-center">
    <div class="container debug">
    <div class="row">
      <div class="col">
        <h5>testimonial</h5>
        <h3><strong>what</strong> people say</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iusto, nihil placeat. Esse laboriosam ex neque architecto consequuntur? Exercitationem, expedita illo.</p>
      </div>
    </div>

    <div class="row row-cols-3">

      <div class="col">
        <div class="card">
          <div class="thumb">
            <img src="/images//szabo-viktor-1266895-unsplash-1024x1024.png" alt="">
          </div>         
          <div class="stars">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-regular fa-star"></i>
            <i class="fa-regular fa-star"></i>
          </div>
          <p><strong>nome</strong></p>
          <p>ruolo</p>
        </div>
      </div>

      <div class="col">
        <div class="card">
          <div class="thumb">
            immagine
          </div>         
          <p>recensione</p>
          <p><strong>nome</strong></p>
          <p>ruolo</p>
        </div>
      </div>

      <div class="col">
        <div class="card">
          <div class="thumb">
            immagine
          </div>         
          <p>recensione</p>
          <p><strong>nome</strong></p>
          <p>ruolo</p>
        </div>
      </div>

    </div>

  </div>
  </div>
  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

img {
  width: 70px;
  border: 3px solid $dark-Secondary;
  border-radius: 50%;
}

</style>