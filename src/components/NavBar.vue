<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <router-link to="/">
<img src="https://drive.google.com/uc?id=DRIVE_FILE_ID1rcwdbH6wK9fCU6BA36xHzkzCnSp" loading='lazy' alt="logo">
    </router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item">
          <router-link to="/" class="nav-link active" >Home</router-link>
          
        </li>
        <li class="nav-item">
          <router-link to="/about" class="nav-link " >About</router-link>
          
        </li>
        <li class="nav-item">
          <router-link to="/resume" class="nav-link" >Resume</router-link>
          
        </li>
        <li class="nav-item">
          <router-link to="/testimonials" class="nav-link " >Testimonials</router-link>
          
        </li>
        <li class="nav-item">
          <router-link to="/projects" class="nav-link" >Projects</router-link>
          
        </li>
        <li class="nav-item">
          <router-link to="/reachMe" class="nav-link" >Reach Me</router-link>
          
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
    export default {
    
    }
</script>

<style scoped>

</style>