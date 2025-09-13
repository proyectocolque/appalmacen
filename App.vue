<template>

  <div id="app">
    <img alt="Logo" src="https://tse1.mm.bing.net/th/id/OIP.GZ84FosySqKw3nQa5oLLPQHaHa?r=0&rs=1&pid=ImgDetMain&o=7&rm=3">
      <div>
    <h1> MI APLICACION DE UN ALMACEN CON VUE.JS</h1>
    <h3>Diseñado los componentes por Carla Colque Condori</h3>
  </div>
  <PresentacionCard
  titulo="Almcacen de Multi Abarrotes"
  />
    <PresentacionCard
      titulo="Bienvenidos al almacen Casa Del Rio"
      linea1="Ofrecemos todo por mayor "
      marca="jiji"
      linea2="Ven y aprovecha la compra de todo tipo de productos"
    />
    <PresentacionCard
      titulo="Asi que animate"
      linea1="Aprovecha que es con aumento cada producto que vas llevar"
      marca="jsjsj"
      linea2="Recuerda que te atenderemos con mucho gusto"
    />
  
  </div>
</template>

<script>
import PresentacionCard from './components/proyecjt.vue'

export default {
  name: 'App',
  components: {
    PresentacionCard
  }
}
</script>


<style>

#app {

  background-color: #1a1a1a;


  background-image: url('https://tse3.mm.bing.net/th/id/OIP._M6NVD8nVqYcZtaD99lzlAHaE7?r=0&rs=1&pid=ImgDetMain&o=7&rm=');
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;

  min-height: 100vh;

  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #01010f;
  margin: 0; 
  padding: 0;
}
</style>