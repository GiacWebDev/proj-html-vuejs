<script>
export default {
  name: 'Portfolio'
}
</script>


<template>

  <div class="container py-5">
    <h5>portfolio</h5>
    <h3><span>latest</span> work</h3>
  
    <div class="carosello debug-db">
      <div class="card-work"></div>
    </div>
  </div>

  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

h3 {
  text-transform: none;
}


</style>