<script>
export default {
  name: 'NavBar',
  props: {
    mainMenu: Object, // array menu Header
    menuItemSelected: String // Aggiungo la prop per l'elemento selezionato
  },
  mounted() {
    console.log('menuItemSelected:', this.menuItemSelected);
  },

}
</script>


<template>

  <div class="nav-bar">
    <div class="container">
  
      <div class="logo">
        <img src="/images/white-logo-2.png" alt="">
      </div>
  
      <div class="menu text-left">
        <ul>
          <!-- ciclo il menù e se sono uguli applico la classe text-active -->
          <li
          v-for="menuItem in mainMenu" 
          :key="menuItem.label">
          <a
          :href="menuItem.href" 
          :class="{ 'text-active': menuItemSelected === menuItem.label }">{{ menuItem.label }}</a></li>
          <li><button class="btns btn-blue ms-3">Sign In</button></li>
        </ul>
      </div>
  
    </div>
  </div>

  
</template>


<style lang="scss" scoped>
@use '../../assets/scss/main.scss' as *;

.nav-bar {
  background-color: $light-primary;
  position: fixed;
  top:0;
  width: 100%;
  padding: 15px 0;
  z-index: 500;
}

.logo {
  display: inline-block;
  width: 30%;

}
.menu {
  text-align: right;
  display: inline-block;
  width: 70%;
  padding-top: 5px;
}
img {
  width: 100px;
}

ul {
  list-style: none;
  li  {
    display: inline-block;
    margin-left: 25px;
    a {
      color: $card-light;
      text-decoration: none;
      &:hover {
        color: $dark-Secondary;
      }
    }
  }
}


</style>