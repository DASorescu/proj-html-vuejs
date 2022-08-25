<template>
  <div class="input-bar">
    <input type="text" placeholder="Search...">
  </div>
</template>


<script>
export default {
name:'searchBar',
}
</script>

<style lang="scss" scoped>
.input-bar{
  font-family: Gylroy-thin , sans-serif;
  border-left: 1px solid #ecf2f9;
  height: 100%;
}
input{
  
    border-width: 0px;
    border-style:none;
    border-color: transparent;
    line-height: 70px;
    padding: 0 1rem;

    vertical-align: middle;
}
</style>