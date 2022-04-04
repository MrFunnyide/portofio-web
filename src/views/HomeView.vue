<template>
  <div style="background-color: #383838; min-height: 590px">
    <!--  Navbar-->
    <nav class="navbar navbar-expand-lg navbar-dark shadow-sm fixed-top" style="background-color: #383838 ">
      <div class="container">
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav m-auto">
            <li class="nav-item  me-3">
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
  <!-- jumbotron-->
  <section class="jumbotron text-center mt-5">
    <img src="../assets/img/MyFoto.png" width="250" alt="Aji Bayu Permadi" class="rounded-circle text-white-50">
    <h1 class="display-3 text-white-50">Aji Bayu Permadi</h1>
    <p class="lead text-white-50">College Student | Junior Web Developer</p>
  </section>
  </div>
  <!--  akhir jumbotron-->
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView'
}
</script>
<style>

</style>
