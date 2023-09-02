<!-- <template>
  <div id="app">
    <Card/>
  </div>
</template>

<script>
import Card from './components/CardJobs.vue'

export default {
  name: 'App',
  components: {
    Card
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>  -->

<template>
  <div id="app" class="app">
    <NavPrincipal />
    <div class="main-content">
      <div class="nav-vertical">
        <NavVertical />
      </div>
      <div class="content">
 
        

        <NavHorizontal />

        <Card/>
        
      </div>
    </div>
    <div class="footer">
      <PiePa />
    </div>
  </div>
</template>

<script>
import Card from './components/CardJobs.vue'
import NavPrincipal from "./components/NavPrincipal.vue";
import NavVertical from "./components/NavVertical.vue";
import NavHorizontal from "./components/NavHorizontal.vue";
import PiePa from "./components/PiePa.vue";

export default {
  name: 'App',
  components: {
    Card,
    NavPrincipal,
    NavVertical,
    NavHorizontal,
    PiePa,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.main-content {
  margin-top: -20px;
  display: flex;
  flex: 1;
}

.nav-vertical {
  width: 700px; /* Ancho de la barra vertical */
  background-color: #ffffff; /* Color de fondo de la barra vertical */
  color: black; /* Color del texto de la barra vertical */
}

.content {
  flex: 1;
  padding: 20px; 
}

.footer {
  background-color:white;
  height: 5vh; /* Altura del footer */
  display: flex;
  justify-content: center;
  align-items: center;
}
</style> 