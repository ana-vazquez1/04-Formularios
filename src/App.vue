<template>
  <div class="container mt-3">
    <Header></Header>
  <Formulario></Formulario>

      
</div>
</template>

<script>
  import Header from "./components/Header.vue";
  import Formulario from "./components/Formulario.vue";
  import TotalProyectos from "./components/TotalProyectos.vue";
  import ProgressBar from "./components/ProgressBar.vue";
  export default{
    components:{
    Header,
    Formulario,
    TotalProyectos,
    ProgressBar
  },
  };
</script>