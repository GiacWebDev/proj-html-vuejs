
<script>
export default {
  name: 'Blog'
}
</script>


<template>
  <div class="container py-5 text-center debug">

    <div class="head">
      <h5>blog</h5>
      <h3><strong>latest</strong> post</h3>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iusto, nihil placeat. Esse laboriosam.</p>
    </div>

    <div class="row d-flex justify-content-between">

      <div class="col col-6 primary-post debug">
        <p>Aprile 21 - by Paul</p>
        <h6>Titolo</h6>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque, debitis.</p>
      </div>

      <div class="col secondary-posts col-3">
        <p>Aprile 21 - by Paul</p>
        <h6>Titolo</h6>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque, debitis.</p>
        <button class="btns btn-white">Read More</button>
      </div>

      <div class="col secondary-posts col-3">
        <p>Aprile 21 - by Paul</p>
        <h6>Titolo</h6>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque, debitis.</p>
        <button class="btns btn-white">Read More</button>
      </div>
    </div>


  </div>
</template>

<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

.head {
  margin-bottom: 50px;
  p {
    width: 550px;
  }
}
.col {
  height: 300px;
  display: flex;
  flex-direction: column;
  justify-content: center; 
  text-align: start;
  border-radius: 20px;
  color: $card-light;
  padding: 35px;
  p {
    margin: 0;
    color: $card-light;
  }
  h6 {
    margin: 0;
    margin: 15px 0;
    color: $card-light;
    font-weight: bold;
  }
}

button {
    width:fit-content;
  }

  
.col.secondary-posts {
  background-color: $light-primary;
  button {
    margin-top: 30px;
  }
}
.col.primary-post {
  justify-content: end; 
  background-image: url(/images/headway-537308-unsplash-1380x703.jpg);
  button {
    margin-top: 30px;
  }
}


</style>