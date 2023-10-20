<script>

import Newsletter from './partials/Newsletter.vue';
import Copyright from './partials/Copyright.vue';


export default {
  name: 'AppFooter',
  components: {
    Newsletter,
    Copyright
  }
}
</script>


<template>

  <footer>

    <Newsletter />
  
    <div class="infos">
      <div class="container">
        <div class="row row-cols-4">
  
          <div class="col">

            <div class="logo-box d-flex align-items-center">
              <div class="image col-3">
                <img src="/images/cropped-cropped-icon-270x270.png" alt="logo">
              </div>
              <div class="logo-text col-9">
                <h5>phlox</h5>
                <h5><strong>corporate</strong></h5>
              </div>
            </div>

            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus fugiat, deserunt provident dignissimos in autem!</p>
          </div>
  
          <div class="col">
            <h6><strong>quick links</strong></h6>
            <ul>
              <li><a href="#">services</a></li>
              <li><a href="#">contact</a></li>
              <li><a href="#">blog</a></li>
            </ul>
          </div>
  
          <div class="col text-center">
            <h6><strong>resources</strong></h6>
            <ul>
              <li><a href="#">art design</a></li>
              <li><a href="#">computer</a></li>
              <li><a href="#">it news</a></li>
              <li><a href="#">networking</a></li>
              <li><a href="#">web security</a></li>
            </ul>
          </div>
  
          <div class="col">
            <h6><strong>contact us</strong></h6>
            <ul>
              <li><a href="#"><strong>address: </strong>patricia c. amedee 4401 waldeck street grapevine nashville, tx 76051</a></li>
              <br>
              <li><a href="#"><strong>phone: </strong>+99 (0) 101 000 888</a></li>
              <li><a href="#"><strong>email: </strong>info@yourdomain.com</a></li>
            </ul>
          </div>
  
          
          
        </div>
      </div>
    </div>

    <Copyright />
  
  </footer>
</template>


<style lang="scss" scoped>
@use '../assets/scss/main.scss' as *;

footer {
  background-color: $light-primary;
  .infos {
    margin: 60px 0;
  }
  .col {
    .logo-box {
      width: 55%;
      margin-bottom: 20px;
        img {
        width: 45px;
        }
      }
      .logo-text {
        margin-left: 6px;
        padding-top: 5px;
          h5 {
          color: $card-light;
          line-height: .5rem;
        }
      }
      h6 {
        color: $card-light;
      }
      p {
        color: $description-text;
      }
      ul {
        padding: 0;
        li {
          list-style: none;
          text-transform: capitalize;
          strong {
            color: white;
          }
          a {
            text-decoration: none;
            color: $description-text;
          }
        }
    } 
  }
}
  
  



</style>