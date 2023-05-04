<template>
  <section class="about-us">
    <div class="row p-4">
      <div class="col-6">
        <img class="float-lg-right" src="@/assets/black_friday.jpg">
      </div>
      <div class="col-12 col-sm-6">
        <h1>Black Friday</h1>
        <h6 class="description-img-1">Gravity will force your feet to the ground. Don’t be afraid, your mind will find your freedom.
           You won’t miss a sunrise. You’ll rise with the sun.
           <br>You’ll never run away from the storm. You will flow with the wind.
           <br>Don’t hesitate to pause. Follow the flow of the moment.
           And then, take the first step towards the new you.
          </h6>
      </div>
    </div>
    <div class="row p-4">
      <div class="text-second col-12 col-sm-6 text-sm-right text-md-right ml-sm-0 ml-md-5 ml-lg-5 ml-xl-5 text-lg-right order-sm-first order-12">
        <h1>New Arribal</h1>
        <h6 class="description-img-2">Gravity will force your feet to the ground. Don’t be afraid, your mind will find your freedom.
           You won’t miss a sunrise. You’ll rise with the sun.
           You’ll never run away from the storm. You will flow with the wind.
           Don’t hesitate to pause. Follow the flow of the moment.
           And then, take the first step towards the new you.
          </h6>
      </div>
      <div class="col-6">
        <img class="img-second" src="@/assets/solde.jpg">
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutUs'
}
</script>

<style scoped>
.about-us img {
  width: 30%;
  min-width: 380px;
  margin-right: 0%;
}
.img-second {
  position: relative;
  left: 10%;
}
.text-second{
  position: relative;
  right: 3.5%;
  margin-right: -8%;
  z-index:1;
}
.description-img-2 {
  width: 65%;
  position: relative;
  left: 35%;
}
.description-img-1 {
  width: 65%;
}
</style>
