<template>
  <div>
    <section id="why-us">
      <div class="section-title container">
        <p>Let's Dream Big Together</p>
        <h2>We are pioneers of the digital approach,using leading-edge technology to simplify procedures and apply executive coaching in the new age of digitalization.</h2>
      </div>
      <div class="row">
        <div class="col"></div>
      </div>
    </section>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import'../assets/scss/style.scss';
#why-us{
  display: flex;
  flex-direction: column;
  p{
    color: $maintheme;
  }
  .section-title{
    padding: 1rem 2rem;
    text-align: center;
    p{
      font-size: 25px;
    }
    h2{
      color: $mainFont;
    }
  }
}
</style>