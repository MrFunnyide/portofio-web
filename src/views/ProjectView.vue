<template>
  <div style="background-color: #56BBF1" >
    <nav class="navbar navbar-expand-lg navbar-dark shadow-sm" style="background-color: #2FA4FF">
      <div class="container">
        <a class="navbar-brand" href="#">Aji Bayu Permadi</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="/">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/project">Projects</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!--  Akhir Navbar-->
    <!--  Project-->
    <section id="project" class="mt-3">
      <div class="container">
        <div class="row text-center">
          <div class="col mb-3">
            <h2>My Projects</h2>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4 mb-3">
            <div class="card" style="width: auto;">
              <img src="../assets/img/app1.jpeg" class="card-img-top" alt="Peduli Lindungi Remake">
              <div class="card-body">
                <h5 class="card-title">Peduli Lindungi Remake</h5>
                <p class="card-text">Ini adalah aplikasi peduli lindungi versi remake.</p>
                <a href="https://github.com/MrFunnyide/app-remake" class="btn btn-primary">Go somewhere</a>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card" style="width: auto;">
              <img src="../assets/img/Appinfo.jpeg" class="card-img-top" alt="Infomation App">
              <div class="card-body">
                <h5 class="card-title">Information App</h5>
                <p class="card-text">aplikasi yang berisikan informasi tentang rumah sakit dll</p>
                <a href="https://github.com/MrFunnyide/Info-App" class="btn btn-primary">Go somewhere</a>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card" style="width: auto;">
              <img src="../assets/img/orderApp.jpg" class="card-img-top" alt="Aplikasi Order Makanan">
              <div class="card-body">
                <h5 class="card-title">Aplikasi Order Makanan</h5>
                <p class="card-text">Ini adalah aplikasi untuk order makanan dalam bentuk yanh sederhana.</p>
                <a href="https://github.com/MrFunnyide/app-remake" class="btn btn-primary">Go somewhere</a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#C2F69B" fill-opacity="1" d="M0,64L26.7,90.7C53.3,117,107,171,160,176C213.3,181,267,139,320,106.7C373.3,75,427,53,480,64C533.3,75,587,117,640,149.3C693.3,181,747,203,800,213.3C853.3,224,907,224,960,186.7C1013.3,149,1067,75,1120,42.7C1173.3,11,1227,21,1280,32C1333.3,43,1387,53,1413,58.7L1440,64L1440,320L1413.3,320C1386.7,320,1333,320,1280,320C1226.7,320,1173,320,1120,320C1066.7,320,1013,320,960,320C906.7,320,853,320,800,320C746.7,320,693,320,640,320C586.7,320,533,320,480,320C426.7,320,373,320,320,320C266.7,320,213,320,160,320C106.7,320,53,320,27,320L0,320Z"></path></svg>
    </section>
    <!--  Akhir Project-->
  </div>
</template>

<script>
export default {
  name: "ProjectView"
}
</script>

<style scoped>
</style>