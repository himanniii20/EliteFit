<template>
  <div class="container" id="about">
    <div class="row">
      <div class="col-sm-12 col-md-6 p-5">
        <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active" data-bs-interval="2000">
              <img alt="about pistons 1" class="d-block w-100"  src="../assets/aboutImage1.png">
            </div>
            <div class="carousel-item active" data-bs-interval="2000">
              <img alt="about pistons 2" class="d-block w-100"  src="../assets/aboutImage2.png">
            </div>
            <div class="carousel-item" data-bs-interval="2000">
              <img alt="about pistons 3" class="d-block w-100"  src="../assets/aboutImage3.png">
            </div>
            <div class="carousel-item" data-bs-interval="2000">
              <img alt="about pistons 4" class="d-block w-100"  src="../assets/aboutImage4.png">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
      <div class="col-sm-12 col-md-6 p-5 my-auto">
        <h2 class="text-start">
          ABOUT PISTONS
        </h2>
        <p class="text-start">
          Established in 1897, our beloved fountain pen haven, 'PISTONS,' has been a haven for pen enthusiasts for
          generations. With a century-long dedication to fine writing instruments, we've bridged tradition and modernity,
          offering a curated selection of vintage and contemporary fountain pens. Our little shop, nestled in the heart of
          town, continues to inspire a love for the art of writing, connecting past and present through the timeless
          elegance of ink on paper.
        </p>
      </div>
    </div>
  </div>
</template>
  
<script>
export default {
  name: 'AboutSection',
}
</script>
  