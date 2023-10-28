<template>
  <div class="header sticky-top">
    <div class="announcement p-1">
      <p class="fs-5 text-center m-0">FREE SHIPPING ON ALL ORDERS</p>
    </div>
    <div class="nav-bar">
      <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-light ">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">PISTONS</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#new">NEW</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#brands">BRANDS</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#collections">COLLECTIONS</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#accessories">ACCESSORIES</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#about">ABOUT</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>
  
<script>
export default {
  name: 'HeaderSection',
}
</script>
  
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>.announcement {
  background-color: #E3E3E3;
}</style>