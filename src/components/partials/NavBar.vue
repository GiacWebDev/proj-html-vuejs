<script>
export default {
  name: 'NavBar'  
}
</script>


<template>

  <div class="container">
    <div class="row row-cols-2">

      <div class="col">
        <p>logo</p>
      </div>

      <div class="col">
       <ul>
        <li><a class="text-active" href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><button class="btns">Sign In</button></li>
       </ul>
      </div>

    </div>
  </div>
  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;


.col {
  display: flex;
  align-items: center;
  color: $card-light;
  ul {
    list-style: none;
    li  {
      display: inline-block;
      margin-right: 25px;
      a {
        color: $card-light;
        text-decoration: none;
      }
    }
  }
}

</style>