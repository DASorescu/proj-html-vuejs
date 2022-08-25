<template>
  <div >
    <MainHeader/>
    <TheMain/>
    <MainFooter/>
  </div>
</template>

<script>

import MainHeader from './components/MainHeader.vue';
import TheMain from './components/TheMain.vue';
import MainFooter from './components/MainFooter.vue';
export default {
  name: 'App',
  components: {
    MainHeader,
    TheMain,
    MainFooter,
  }
}
</script>

<style lang="scss">
@import'./assets/scss/style.scss';
@font-face {
  font-family: "Gilroy";
  src: local("Gilroy-regular"),
  url(./fonts/Gilroy-Regular.ttf) format("truetype");
  src: local('Gilroy-medium'),
  url(./fonts/Gilroy-Medium.ttf) format("truetype");
  src: local('Gilroy-bold'),
  url(./fonts/Gilroy-Bold.ttf) format("truetype");
  src: local('Gilroy-light'),
  url(./fonts/Gilroy-Light.ttf) format("truetype");

}
</style>
