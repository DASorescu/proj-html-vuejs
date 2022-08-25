<template>
  <div id="jumbotron" >
    <div class="container">
      <div class="title">
        <h3>New Challenges, New Skills</h3>
        <h1>BUILD YOUR OWN LIFE COACHING BUSINESS</h1>
        <p>Whole-Life Business Coaching for committed entrepreneurs</p>
      </div>
      <figure class="home-avatar">
        <img src="../assets/images/home-business-hero-global-image.png" alt="map" class="jumbo-map img-fluid">
        <img src="../assets/images/home-business-hero-avatar.png" alt="avatar" class=" img-fluid avatar-img">
      </figure>
    </div>
    </div>
</template>

<script>
export default {
name: 'MainJumbotron'
}
</script>

<style lang="scss">
@import '../assets/scss/style.scss';
#jumbotron{
  background-color: #eceeef;
  
  .container{
  display: flex;
  justify-content: space-between;
  }
}

.title{
  width: 33%;
  padding: 0 3rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  h3{
    font-size: 25px;
    font-weight: lighter;
     font-family: Gilroy-light , sans-serif;
    color: $maintheme;
  }
  h1{

    font-family: Gilroy-bold , sans-serif;
    font-size: 50px;
    color: $mainFont;
  }
  p{
    font-size: 20px;
    font-family: Gilroy-regular, sans-serif;
    color: #797979;
  }
}
.home-avatar{
  width: 60%;
  margin: 0%;
  position: relative;
  .avatar-img{
    position: absolute;
    bottom: 0%;
    right: 0%;
    
    transform : translateX(-200px)
  }
  .jumbo-map{
    transform: rotate(-0.25turn)  
  }
}
</style>
