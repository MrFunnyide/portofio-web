<template>
<<<<<<< HEAD
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
=======
 <div style="background-color: #C2F69B">
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
   <!--  awal Contact-->
   <section id="contact">
     <div class="container mt-5">
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
               <input type="text" class="form-control" id="name" aria-describedby="name">
             </div>
             <div class="mb-3">
               <label for="email" class="form-label">Email</label>
               <input type="email" class="form-control" id="email" aria-describedby="email">
             </div>
             <div class="mb-3">
               <label for="pesan" class="form-label">Pesan</label>
               <textarea class="form-control" id="pesan" rows="3"></textarea>
             </div>
             <button type="submit" class="btn btn-primary">Kirim</button>
           </form>
         </div>
       </div>
     </div>
     <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#a4d7e1" fill-opacity="1" d="M0,192L40,181.3C80,171,160,149,240,122.7C320,96,400,64,480,90.7C560,117,640,203,720,250.7C800,299,880,309,960,288C1040,267,1120,213,1200,165.3C1280,117,1360,75,1400,53.3L1440,32L1440,320L1400,320C1360,320,1280,320,1200,320C1120,320,1040,320,960,320C880,320,800,320,720,320C640,320,560,320,480,320C400,320,320,320,240,320C160,320,80,320,40,320L0,320Z"></path></svg>
   </section>
   <!--  Akhir contact-->
 </div>
>>>>>>> 51c262aa316a1bf19fe93db82b2450617ec9867f
</template>

<script>
export default {
  name: "ContactView"
}
</script>

<style scoped>

</style>