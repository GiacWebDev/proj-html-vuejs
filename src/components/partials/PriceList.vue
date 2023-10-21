<script>
export default {
  nome: 'PriceList',
}
</script>


<template>

<div class="our-prices white-text text-center py-5 ">
  <div class="container">

    <div class="row">
      <div class="col head">
        <h5>price list</h5>
        <h3><strong>our</strong> price</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iusto, nihil placeat adipisicing elit. Iusto, nihil placeat</p>
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
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
            </ul>
            <button class="btns btn-orange">Order Now 
              <i class="fa-solid fa-arrow-right-long" style="color: #ffffff;"></i>
            </button>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="card btn-orange">
          <div class="big-number">
            <p>60</p>
          </div>
          <div class="card-body">
            <h3 class="card-title">Designing</h3>
            <p class="card-text">PROCESS</p>
            <p>$</p>
            <h3>60</h3>
            <p>Per Month</p>

            <ul>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
            </ul>
            <button class="btns btn-white">Order Now 
              <i class="fa-solid fa-arrow-right-long"></i>
            </button>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="card">
          <div class="big-number">
            <p>80</p>
          </div>
          <div class="card-body">
            <h3 class="card-title">Designing</h3>
            <p class="card-text">PROCESS</p>
            <p>$</p>
            <h3>80</h3>
            <p>Per Month</p>

            <ul>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
              <li><span>creative</span> design enabled</li>
            </ul>
            <button class="btns btn-orange">Order Now 
              <i class="fa-solid fa-arrow-right-long" style="color: #ffffff;"></i>
            </button>
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
  .col.head p {
    width: 550px;
    color: $card-light;
    margin-bottom: 50px;
  }
  .card.btn-orange {
    color: $card-light;
    p {
      color: $card-light;
    }
    li {
      color: $card-light;
    }
    .btn-white {
      color: $light-Seconday;
      i {
        color: $light-Seconday;
      }
    }
  }
  .col {
    position: relative;
    .card {
      border-radius: 20px!important;
      .big-number {
      position: absolute;
      font-size: 250px;
      font-weight: 700;
      opacity: .1;
      top: 0px;
      right: 0px;
      line-height: 12rem;
    }
      .card-body {
        h3 {
          font-weight: bold;
          font-size: 4rem;
        }
        ul {
          padding: 0;
          margin: 40px 0;
          li {
            text-transform: capitalize;
            color: $description-text;
            margin: 5px 0;
            span {
              color: $dark-primary;
            }
          }
        }
        button {
          width: 200px;
          font-weight: bold;
          margin-bottom: 30px;
          i {
            margin-left: 50px;
            font-weight: bold;
          }
        }
      }
      h3.card-title {
        font-size: 2rem;
      }
    }
  }
}

</style>