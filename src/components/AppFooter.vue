<script>

import Newsletter from './partials/Newsletter.vue';
import Copyright from './partials/Copyright.vue';


export default {
  name: 'AppFooter',
  components: {
    Newsletter,
    Copyright
  },
  props: {
    QuickLinks: Array,
    Resources: Array,
    menuItemSelected: String
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

            <img src="/images/white-logo-2.png" alt="">

            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus fugiat, deserunt provident dignissimos in autem!</p>
          </div>
  
          <div class="col ps-5">
            <h6><strong>quick links</strong></h6>
            <ul>
              <li 
              v-for="itemMenu in QuickLinks" 
              :key="itemMenu.label"
              :class="{'text-active-white' : itemMenu === menuItemSelected }">
              <a :href="itemMenu.href">{{ itemMenu.label }}</a>
              </li>
            </ul>
          </div>
  
          <div class="col ps-3">
            <h6><strong>resources</strong></h6>
            <ul>
              <li v-for="itemResources in Resources" 
              :key="itemResources.label"
              :class="{'text-active-white' : itemResources === menuItemSelected }">
              <a :href="itemResources.href">{{ itemResources.label }}</a></li>
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
  background-image: linear-gradient(to bottom, white 0%, white 12vh, $light-primary 12vh, $light-primary 100%);
  .infos {
    margin: 60px 0;
  }
  .col {
    img {
      width: 120px;
      margin-bottom: 20px;
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