
<script>
export default {
  name: 'Chat'
}
</script>


<template>

  <div class="logo-chat d-flex align-items-center justify-content-center debug">
    <i class="fa-regular fa-comment fa-flip-horizontal" style="color: #ffffff;"></i>
  </div>
  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

.logo-chat {
  position: absolute;
  // bottom: 20px;
  right: 20px;
  border-radius: 50%;
  width: 60px;
  height: 60px;
  background-color: #527CEB;
  i {
    font-size: 1.6rem;
  }
}

</style>