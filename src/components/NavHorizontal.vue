<template>
    <nav class="horizontal-navbar" >

      <!-- Barra de búsqueda -->
      <div class="search-bar">
        <input type="text" placeholder="Busca por cargo, salario, ubicación o empresa">
        <button><i class="fas fa-search"></i></button>
      </div>
      
    <div class="spacer"></div>

      <div class="navbar-item has-dropdown is-hoverable">
        <a id="xa" class="navbar-link">Area</a>
        <div class="navbar-dropdown">
          <a class="navbar-item" href="#">Opción 1</a>
          <a class="navbar-item" href="#">Opción 2</a>
        </div>
      </div>
      
      
      
      <!-- Dropdown 2 -->
      <div class="navbar-item has-dropdown is-hoverable">
        <a id="xa" class="navbar-link">Cargo</a>
        <div class="navbar-dropdown">
          <a class="navbar-item" href="#">Opción 1</a>
          <a class="navbar-item" href="#">Opción 2</a>
        </div>
      </div>
  
      <!-- Dropdown 3 -->
      <div class="navbar-item has-dropdown is-hoverable">
        <a id="xa" class="navbar-link">Salario</a>
        <div class="navbar-dropdown">
          <a class="navbar-item" href="#">Opción 1</a>
          <a class="navbar-item" href="#">Opción 2</a>
        </div>
      </div>
  
      <!-- Dropdown 4 -->
      <div class="navbar-item has-dropdown is-hoverable">
        <a  id="xa" class="navbar-link">Ubicacion</a>
        <div class="navbar-dropdown">
          <a class="navbar-item" href="#">Opción 1</a>
          <a class="navbar-item" href="#">Opción 2</a>
        </div>
      </div>
    </nav>
  </template>
  

  <style scoped>
  .horizontal-navbar {
    display: flex;
    border: none;
    align-items: center;
    margin-left: 5px;
    width: 90vw;
    height: 65px;
    color: white;
  }
  
  .search-bar {
    display: flex;
    align-items: center;
    width: 45vw;
    padding: 5px;
    margin-right: 19px; 
  }
  
  .search-bar input {
    flex: 1;
    border: none;
    outline: none;
    margin-left: 70px;
    height: 40px;
    width: 820px;
    border-radius: 5px;
  }
  
  .search-bar button {
    background: none;
    border: none;
    cursor: pointer;
  }
  
  .spacer {
    flex: 1; /* Espacio entre la barra de búsqueda y los dropdowns */
  }
  
  .navbar-horizontal .navbar-item {
    text-align: end;
  }
  
  .horizontal-navbar {
    background-color: #3a8ced;
  }

  #xa{
    color: black;
    border-radius: 20px;
    border: #ccc;
    border-style: solid;
    margin-left: 10px;
    margin-right: 15px;
    height: 30px;
  }
  </style>
  