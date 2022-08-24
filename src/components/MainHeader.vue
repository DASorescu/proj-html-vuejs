<template>
  <div id="main-header">
    <img src="../assets/images/dark-logo.png" alt="logo" class="logo-image">
    <navBar/>
    <select name="" id=""></select>
    <searchBar/>
  </div>
</template>

<script>
import navBar from './navBar.vue';
import searchBar from './searchBar.vue';
export default {
  name:'MainHeader',
  components :{
    navBar,
    searchBar,
  }
}
</script>

<style lang="scss" scooped>
@import '../assets/scss/style.scss';

#main-header{
  height: 80px;
  margin-left: 10%;
  display:flex;
  align-items: center;
}

.logo-image{
  height: 20px;
  width: auto;
}


</style>