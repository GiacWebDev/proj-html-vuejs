<script>
export default {
    name: 'Testimonial'
}
</script>


<template>

  <div class="testimonial my-5 text-center">
    <div class="container">
    <div class="row">
      <div class="col head">
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
          <div class="marks">
            <p>"</p>
          </div>     
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae accusamus maxime minus corporis sed. Quam!</p>
          <h6><strong>michkel anegl</strong></h6>
          <p>Marketing Management</p>
        </div>
      </div>

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
          <div class="marks">
            <p>"</p>
          </div>         
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae accusamus maxime minus corporis sed. Quam!</p>
          <h6><strong>michkel anegl</strong></h6>
          <p>Marketing Management</p>
        </div>
      </div>

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
          <div class="marks">
            <p>"</p>
          </div>         
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae accusamus maxime minus corporis sed. Quam!</p>
          <h6><strong>michkel anegl</strong></h6>
          <p>Marketing Management</p>
        </div>
      </div>

    
    </div>

  </div>
  </div>
  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

.col.head {
  margin: 50px 0;
  p {
    width: 550px;
  }
} 


.card {
  padding: 30px;
  border: none;
  img {
  width: 70px;
  border: 3px solid $dark-Secondary;
  border-radius: 50%;
  }
  .marks {
    font-size: 200px;
    font-style: italic;
    p {
      color: rgb(221, 221, 221);
      line-height: 20px;
      font-weight: bold;
    }
  }
  .stars {
    i {
      font-size: .8rem;
      color: $dark-Secondary;
      margin: 20px 0;
    }
  }
}

</style>