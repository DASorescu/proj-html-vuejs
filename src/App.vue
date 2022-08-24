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

</style>
