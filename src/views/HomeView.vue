<template>
  <!--  Navbar-->
  <nav class="navbar navbar-expand-lg navbar-dark shadow-sm fixed-top" style="background-color: #2FA4FF ">
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
  <!-- jumbotron-->
  <section class="jumbotron text-center mt-5">
    <img src="../assets/img/MyFoto.png" width="250" alt="Aji Bayu Permadi" class="rounded-circle">
    <h1 class="display-4">Aji Bayu Permadi</h1>
    <p class="lead">College Student | Junior Web Developer</p>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#E8FFC2" fill-opacity="1" d="M0,224L30,224C60,224,120,224,180,213.3C240,203,300,181,360,154.7C420,128,480,96,540,106.7C600,117,660,171,720,170.7C780,171,840,117,900,128C960,139,1020,213,1080,224C1140,235,1200,181,1260,170.7C1320,160,1380,192,1410,208L1440,224L1440,320L1410,320C1380,320,1320,320,1260,320C1200,320,1140,320,1080,320C1020,320,960,320,900,320C840,320,780,320,720,320C660,320,600,320,540,320C480,320,420,320,360,320C300,320,240,320,180,320C120,320,60,320,30,320L0,320Z"></path></svg>
  </section>

  <!--  akhir jumbotron-->
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView'
}
</script>
