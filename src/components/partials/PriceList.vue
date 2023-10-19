<script>
export default {
  nome: 'OurPricing',
}
</script>


<template>

<div class="our-prices white-text text-center">
  <div class="container">

    <div class="row">
      <div class="col">
        <h5>price list</h5>
        <h3><strong>our</strong> price</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iusto, nihil placeat. Esse laboriosam ex neque architecto consequuntur? Exercitationem, expedita illo.</p>
      </div>
    </div>

    <div class="row row-cols-3">

      <div class="col">
        <div class="card">
          <div class="big-number">
            <p>40</p>
          </div>
          <div class="card-body">
            <h3 class="card-title">Designing</h3>
            <p class="card-text">PROCESS</p>
            <p>$</p>
            <h3>40</h3>
            <p>Per Month</p>

            <ul>
              <li>Creative</li>
              <li>Creative</li>
              <li>Creative</li>
              <li>Creative</li>
              <li>Creative</li>
            </ul>
            <button class="btns">Order Now</button>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="card">
          <div class="big-number">
            <p>40</p>
          </div>
          <div class="card-body">
            <h3 class="card-title">Designing</h3>
            <p class="card-text">PROCESS</p>
            <p>$</p>
            <h3>40</h3>
            <p>Per Month</p>

            <ul>
              <li>Creative</li>
              <li>Creative</li>
              <li>Creative</li>
              <li>Creative</li>
              <li>Creative</li>
            </ul>
            <button class="btns">Order Now</button>
          </div>
        </div>
      </div>
      
      <div class="col">
        <div class="card">

          <div class="big-number">
            <p>40</p>
          </div>
          <div class="card-body">
            <h3 class="card-title">Designing</h3>
            <p class="card-text">PROCESS</p>
            <p>$</p>
            <h3>40</h3>
            <p>Per Month</p>

            <ul>
              <li>Creative</li>
              <li>Creative</li>
              <li>Creative</li>
              <li>Creative</li>
              <li>Creative</li>
            </ul>
            <button class="btns">Order Now</button>
          </div>
      
        </div>
      </div>

    </div>
  </div>
</div>
  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

.our-prices {
  background-color: $light-primary;
}

</style>