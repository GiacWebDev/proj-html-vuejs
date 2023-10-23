<script>
export default {
  name: 'Portfolio'
}
</script>


<template>
  <div class="portfolio">
    <div class="container py-5">

      <div class="top">

        <div class="info">
          <h5>portfolio</h5>
          <h3><span>latest</span> work</h3>
        </div>
        
        <div class="arrows">
          <div class="arrow left">
            <i class="fa-solid fa-arrow-left-long" style="color: #b6246e;"></i>
          </div>
          <div class="arrow right">
            <i class="fa-solid fa-arrow-right-long" style="color: #b6246e;"></i>
          </div>
        </div>
        
      </div>
    </div>

    <div class="wrapper">
      <ul class="carousel">

        <li class="card">
          <img src="/images/8wa60okr-1-790x576.jpg" alt="cover">
          <div class="bottom">
            <h6>Basket of Flower on table</h6>
            <p>Branding Strategy</p>
          </div>
        </li>

        <li class="card">
          <img src="/images/8wa60okr-1-790x576.jpg" alt="cover">
          <div class="bottom">
            <h6>Basket of Flower on table</h6>
            <p>Branding Strategy</p>
          </div>
        </li>

        <li class="card">
          <img src="/images/8wa60okr-1-790x576.jpg" alt="cover">
          <div class="bottom">
            <h6>Basket of Flower on table</h6>
            <p>Branding Strategy</p>
          </div>
        </li>

        <li class="card">
          <img src="/images/8wa60okr-1-790x576.jpg" alt="cover">
          <div class="bottom">
            <h6>Basket of Flower on table</h6>
            <p>Branding Strategy</p>
          </div>
        </li>

        <li class="card">
          <img src="/images/8wa60okr-1-790x576.jpg" alt="cover">
          <div class="bottom">
            <h6>Basket of Flower on table</h6>
            <p>Branding Strategy</p>
          </div>
        </li>

      </ul>
    </div>

  </div>
  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;


.portfolio {
  padding: 50px 0;
}
.top {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: end;
  .info {
   margin: 0; 
   h3 {
     text-transform: none;
   }
  }
  .arrows {
    display: flex;
    flex-direction: row;
    width: 100px;
    height: fit-content;
    margin: 0;
    text-align: end;
    .arrow {
      border: 1px solid #b6246e;
      width: fit-content;
      padding: 5px 8px;
      border-radius: 50%;
      cursor: pointer;
    }
  }
}

.wrapper {
  max-width: 1100px;
  width: 100%;
  .carousel {
    display: grid;
    grid-auto-flow: column;
    grid-auto-columns: calc((100% / 3) - 12px);
    gap: 16px;
    overflow: hidden;
    height: 350px;
    .card {
      height: 300px;
      background-color: white;
      border-radius: 20px;
      box-shadow: 0px 10px 15px 3px rgba(0,0,0,0.1);
      border: none;
      cursor: pointer;
      img {
        height: 250px;
        width: 100%;
        border-radius: 20px;
      }
      .bottom {
        width: 100%;
        padding: 15px 25px;
        display: flex;
        flex-direction: row;
        h6 {
          display: inline-block;
          margin-right: 15px;
          text-transform: none;
          font-size: .8rem;
          font-weight: bold;
        }
        p {
          font-size: .8rem;
        }
        
      }
    }
  }
}



</style>