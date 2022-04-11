<template>
  <div style="background-color: #383838; min-height: 640px">
    <nav class="navbar navbar-expand-lg navbar-dark shadow-sm" style="background-color: #383838">
      <div class="container">
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav m-auto">
            <li class="nav-item">
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
              <a class="nav-link" href="/story">Journey Of Life</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!--  Akhir Navbar-->
    <!--  Project-->
    <section id="project" class="mt-4">
      <div class="container">
        <div class="row text-center">
          <div class="col mb-3">
            <h2 class="text-white-50">My Projects</h2>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4 mb-3">
            <div class="card text-white-50" style="width: auto; background-color: #3A3845">
              <img src="../assets/img/app1.jpeg" class="card-img-top" alt="Peduli Lindungi Remake">
              <div class="card-body">
                <h5 class="card-title">Peduli Lindungi Remake</h5>
                <p class="card-text">Ini adalah aplikasi peduli lindungi versi remake.</p>
                <a href="https://github.com/MrFunnyide/app-remake" class="btn btn-outline-dark text-white-50">Go somewhere</a>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card text-white-50" style="width: auto; background-color: #3A3845">
              <img src="../assets/img/Appinfo.jpeg" class="card-img-top" alt="Infomation App">
              <div class="card-body">
                <h5 class="card-title">Information App</h5>
                <p class="card-text">aplikasi yang berisikan informasi tentang rumah sakit dll</p>
                <a href="https://github.com/MrFunnyide/Info-App" class="btn btn-outline-dark text-white-50">Go somewhere</a>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
<!-- <<<<<<< HEAD -->
            <div class="card text-white-50" style="width: auto; background-color: #3A3845">
=======
            <div class="card" style="width: auto;">
              <img src="../assets/img/orderApp.jpg" class="card-img-top" alt="Aplikasi Order Makanan">
                <a href="https://github.com/MrFunnyide/order-app" class="btn btn-outline-dark text-white-50">Go somewhere</a>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card text-white-50" style="width: auto; background-color: #3A3845">
              <img src="../assets/img/firstApp.png" class="card-img-top" alt="Peduli Lindungi Remake">
              <div class="card-body">
                <h5 class="card-title">Nota App</h5>
                <p class="card-text">Ini adalah aplikasi nota app untuk pembayaran.</p>
                <a href="https://github.com/MrFunnyide/nota-App" class="btn btn-outline-dark text-white-50">Go somewhere</a>
              </div>
            </div>
          </div><div class="col-md-4 mb-3">
          <div class="card text-white-50" style="width: auto; background-color: #3A3845">
            <img src="../assets/img/firstApp.png" class="card-img-top" alt="Peduli Lindungi Remake">
            <div class="card-body">
              <h5 class="card-title">First App</h5>
              <p class="card-text">Ini adalah aplikasi pertama yang saya buat di android studio</p>
              <a href="https://github.com/MrFunnyide/first-app" class="btn btn-outline-dark text-white-50">Go somewhere</a>
            </div>
          </div>
        </div><div class="col-md-4 mb-3">
          <div class="card text-white-50" style="width: auto; background-color: #3A3845">
            <img src="../assets/img/firstApp.png" class="card-img-top" alt="Peduli Lindungi Remake">
            <div class="card-body">
              <h5 class="card-title">Second App</h5>
              <p class="card-text">Ini adalah aplikasi kedua yang saya buat di andorid studio.</p>
              <a href="https://github.com/MrFunnyide/app-remake" class="btn btn-outline-dark text-white-50">Go somewhere</a>
            </div>
          </div>
        </div>
        </div>
      </div>
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