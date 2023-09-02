<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" id="imga" href="#">
          <img src="../assets/logopeaku.png" alt="logo" class="logo-image">
        </a>
      </div>
  
    
        <div class="navbar-end" style="display: flex; align-items: center;">
  
          <a class="navbar-item custom-link" href="#">Empleos</a>
          <a class="navbar-item custom-link" href="#">Bootcamp</a>
          <a class="navbar-item custom-link" href="#">Sobre Nosotros</a>
  
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link">
              Para Profesionales
            </a>
            <div class="navbar-dropdown">
                <a class="navbar-item" href="#">Inicio</a>
                <a class="navbar-item" href="#">Empleos</a>
                <a class="navbar-item" href="#">Cursos y Retos</a>
                <a class="navbar-item" href="#">Preguntas</a>
                <a class="navbar-item" href="#">Profesores</a>
                <a class="navbar-item" href="#">Bootcamp</a>
            </div>
          </div>
  
          <div class="navbar-item">
            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link">
                Para Empresas
              </a>
              <div class="navbar-dropdown">
                <a class="navbar-item" href="#">Inicio</a>
                <a class="navbar-item" href="#">Publicar Empleo</a>
                <a class="navbar-item" href="#">Nuestro Proceso</a>
                <a class="navbar-item" href="#">Precios</a>
                <a class="navbar-item" href="#">Pruebas Online</a>
                <a class="navbar-item" href="#">Nominas</a>
                <a class="navbar-item" href="#">Blog</a>
                <a class="navbar-item" href="#">Comercial</a>
                <a class="navbar-item" href="#">Calculadora De Salario</a>
              </div>
            </div>
          </div>
  
          <div class="navbar-item">
            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link">
                Idioma
              </a>
              <div class="navbar-dropdown">
                <a class="navbar-item" href="#">Español</a>
                <a class="navbar-item" href="#">Inglés</a>
                <a class="navbar-item" href="#">Portugues</a>
              </div>
            </div>
          </div>
        </div>
    </nav>
  
  
  </template>
  
  <script>
  export default {
    data() {
      return {
        isBurgerActive: false,
      };
    },
    methods: {
      toggleBurger() {
        this.isBurgerActive = !this.isBurgerActive;
        
      },
      /*funciona para al pasar el mouse por el Deopdown despliegue el menu*/
      toggleDropdown() {
        this.isDropdownActive = !this.isDropdownActive;
      },
    },
  };
  
  </script>
  
  <style>
  .navbar{
    margin-top: -60px;
  }
  .logo-image{
    height: 500px;
    width: 50px;
  }
  #lis a:hover{
    color: black;
  }
  
  .navbar-item a {
    text-decoration: none !important;
    color: gray !important;
  }
  
  /* Cambia el color al pasar el mouse sobre los enlaces dropdown */
  .navbar-item a:hover {
    color: black !important;
  }
  .custom-link {
    text-decoration: none !important;
    color: gray !important;
  }
  
  /* Cambia el color al pasar el mouse sobre los enlaces */
  .custom-link:hover {
    color: black !important;
  }
  </style>
  