<template>
  <div id="navbar">
    <ul>
        <li>Home</li>
        <li>Pages</li>
        <li>Courses</li>
        <li>Features</li>
        <li>Blog</li>
        <li>Shop</li>
    </ul>
  </div>
</template>

<script>
export default {
name:'navBar'
}
</script>

<style lang="scss" scoped>
@import'../assets/scss/style.scss';

#navbar{
    flex-basis: 60%;
}
ul{
    font-family: Gilroy-bold ,sans-serif;
    font-size: 17px;
    color: $adseccolor;
    padding: 0%;
    margin: 0%;
    list-style-type: none;
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    justify-content: flex-end;
    li{
        
        text-align: center;
        width: calc(100% / 8);
    }
}
</style>