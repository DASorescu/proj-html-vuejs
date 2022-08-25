<template>
  <div>
    <div id="main-header">
      <img src="../assets/images/dark-logo.png" alt="logo" class="logo-image">
      <navBar/>
      <ul>
        <li  class="active">
          <img src="../assets/images/en.png" alt="en" class="p-1">
          <span>ENGLISH</span>
        </li>
        <!-- <li>
          <img src="../assets/images/de.png" alt="de" class="p-1">
          <span>DEUSTECH</span>
        </li>
        <li>
          <img src="../assets/images/fr.png" alt="fr" class="p-1">
          <span>FRANCOIS</span>
        </li> -->
      </ul>
      <searchBar/>
    </div>
    <MainJumbotron/>
  </div>
</template>

<script>
import navBar from './navBar.vue';
import searchBar from './searchBar.vue';
import MainJumbotron from './MainJumbotron.vue';
export default {
  name:'MainHeader',
  components :{
    navBar,
    searchBar,
    MainJumbotron,
  
},
  methods:{
    makeActive(){

    }
  }
}
</script>

<style lang="scss" scoped>
@import '../assets/scss/style.scss';

#main-header{
  position: relative;
  z-index: 1;
  background-color: #fefefe;
  height: 70px;
  margin-right: 0%;
  width: 100%;
  display:flex;
  align-items: center;
  justify-content: flex-end;
}

.logo-image{
  height: 25px;
  width: auto;
}

#language{
  border: none;
  height: 70px;
}

ul{
  margin: 0%;
  padding: 0%;
  flex-wrap: wrap;
  flex-direction: column;
  width: 15%;
  list-style-type: none;
  font-family: Gilroy-Bold, sans-serif;
  li{
    width:100%;
    display: flex;
    align-items: center;
    display: none;
    &.active{
      display: flex;
    }
  };
  
}

</style>
