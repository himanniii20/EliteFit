<template>
    <div class="container">
      <div class="my-4">
        <h1>TESTIMONIALS</h1>
      </div>
      <div class="row">
        <!-- <div class="testimonial col-md-3 col-sm-12 m-auto p-2">
          <div class="hover-txt">
            HI
          </div>
          <img src="../assets/testimonialAlex.png" class="w-75" alt="testimonialAlex">
        </div> -->
        <div class="col-md-3 col-sm-12 m-auto p-2">
          <img src="../assets/testimonialAlex.png" class="w-75" alt="testimonialAlex">
        </div>
        <div class="col-md-3 col-sm-12 m-auto p-2">
          <img src="../assets/testimonialDavid.png" class="w-75" alt="testimonialDavid">
        </div>
        <div class="col-md-3 col-sm-12 m-auto p-2">
          <img src="../assets/testimonialEmily.png" class="w-75" alt="testimonialEmily">
        </div>
        <div class="col-md-3 col-sm-12 m-auto p-2">
          <img src="../assets/testimonialLisa.png" class="w-75" alt="testimonialLisa">
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'TestimonialsSection',
  }
  </script>

<style scoped>
.testimonial{
  background-image: url("../assets/testimonialAlex.png");
  background-repeat: none;
  background-size: cover;
}
.hover-txt:hover{
  background: #000000;
  opacity: 0;
}
</style>
  
  