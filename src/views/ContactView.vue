<template>
  <div style="background-color: #383838; min-height: 650px">
    <nav class="navbar navbar-expand-lg navbar-dark shadow-sm " style="background-color: #383838">
      <div class="container">
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav m-auto">
            <li class="nav-item  me-3">
              <a class="nav-link" aria-current="page" href="/">Home</a>
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
    <!--  awal Contact-->
    <section id="contact" class="text-white-50">
      <div class="container mt-4">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>Contact Me</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-6">
            <form>
              <div class="mb-3">
                <label for="name" class="form-label">Nama Lengkap</label>
                <input type="text" class="form-control btn-dark" id="name" aria-describedby="name">
              </div>
              <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control  btn-dark" id="email" aria-describedby="email">
              </div>
              <div class="mb-3">
                <label for="pesan" class="form-label">Pesan</label>
                <textarea class="form-control  btn-dark" id="pesan" rows="3"></textarea>
              </div>
              <button type="submit" class="btn btn-outline-dark text-white-50 ps-5 pe-5">Kirim</button>
            </form>
          </div>
        </div>
      </div>
    </section>
  </div>
  <!--  Akhir contact-->
</template>

<script>
export default {
  name: "ContactView"
}
</script>

<style scoped>

</style>