<template>

  <section class="src-components-navbar">
       <nav class="navbar navbar-expand-md navbar-dark bg-dark">
      <router-link to="/">
        <a class="navbar-brand" href="#">Inicio</a>
      </router-link>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/ingreso">
              <a class="nav-link" href="#">Ingreso</a>
            </router-link>
          </li>
         </ul>
      </div>
    </nav>
  </section>
</template>
<script>


<style scoped lang="css">
  .src-components-navbar {

  }
</style>
