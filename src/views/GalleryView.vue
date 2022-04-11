<template>
  <div style="background-color: #383838; min-height: 650px">
    <nav class="navbar navbar-expand-lg navbar-dark shadow-sm" style="background-color: #383838 ">
      <div class="container">
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav m-auto">
            <li class="nav-item me-3">
              <a class="nav-link " aria-current="page" href="/">Home</a>
            </li>
            <li class="nav-item  me-3">
              <a class="nav-link" href="/about">About</a>
            </li>
            <li class="nav-item  me-3">
              <a class="nav-link" href="/project">Projects</a>
            </li>
            <li class="nav-item  me-3">
              <a class="nav-link" href="/contact">Contact</a>
            </li>
            <li class="nav-item  me-3">
              <a class="nav-link" href="/story">Gallery</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="position-absolute top-50 start-50 translate-middle">
      <div id="carouselExampleIndicators" class="carousel slide m-5 w-auto" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../assets/img/firstFoto.jpg" class="d-block w-100" >
          </div>
          <div class="carousel-item">
            <img src="../assets/img/foto1.jpg" class="d-block w-100">
          </div>
          <div class="carousel-item">
            <img src="../assets/img/foto2.jpg" class="d-block w-100">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "StoryView"
}
</script>

<style scoped>

</style>