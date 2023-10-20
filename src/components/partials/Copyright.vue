
<script>
export default {
  name: 'Copyright',  
}
</script>


<template>

  <div class="copyright">
    <div class="container">
      <div class="row row-cols-2 ">
  
        <div class="col">
          <p>© 2020 Phlox. All Right Reserved</p>
        </div>
  
        <div class="col">
          <ul>
            <li><a href="#">
              <i class="fa-brands fa-instagram" style="color: #ffffff;"></i>
            </a></li>
            <li>
              <i class="fa-brands fa-linkedin-in" style="color: #ffffff;"></i>
            </li>
            <li>
              <i class="fa-brands fa-facebook-f" style="color: #ffffff;"></i>
            </li>
            <li>
              <i class="fa-brands fa-twitter" style="color: #ffffff;"></i>
            </li>
  
          </ul>
        </div>
      
      </div>
    </div>
  </div>

  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

.copyright {
  border-top: 1px solid #81829a77;
  color: white;
  padding-top: 30px;
  ul {
    list-style: none;
    text-align: end;
    li {
      display: inline-block;
      margin: 0 15px;
      i {
        font-size: 1rem;
      }
    }
  }
}

</style>