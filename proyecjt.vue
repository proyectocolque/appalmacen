
<template>
  <div class="presentacion-card">
    <h1>{{ titulo }}</h1>
    <p>{{ linea1 }} <span class="resaltado">{{ marca }}</span></p>
    <p>{{ linea2 }}</p>
  </div>
</template>

<script>
export default {
  name: 'PresentacionCard',
  props: {
    titulo: {
      type: String,
      default: 'Título por defecto'
    },
    linea1: {
      type: String,
      default: ''
    },
    linea2: {
      type: String,
      default: ''
    },
    marca: {
      type: String,
      default: 'Vue.js'
    }
  }
}
</script>

<style scoped>
.presentacion-card {
  background: rgba(117, 196, 196, 0.429);
  padding: 30px;
  border-radius: 12px;
  text-align: center;
  max-width: 600px;
  margin: 20px auto;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
}

.presentacion-card h1 {
  color: rgb(56, 4, 34);
  margin-bottom: 20px;
  font-size: 2.5rem;
}

.presentacion-card p {
  font-size: 1rem;
  color: rgb(1, 32, 5);
  margin: 10px 0;
}

.resaltado {
  background: palevioletred;
  font-size: 1.2rem;
  padding: 2px 4px;
  border-radius: 4px;
}
</style>
