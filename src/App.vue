<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
<!-- App.vue -->
<style>
  /* Estilos globales */
/* Estilos globales */
body {
  font-family: 'Roboto', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #000000;
}

#app {
  max-width: 800px;
  margin: 40px auto;
  padding: 5px;
  background-color: #000000;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  margin-top: -0.5rem;
}

/* Estilos para HomeView */
.search-container {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 20px;
}

.search-container input {
  margin: 0;
  padding: 1rem;
  border: none;
  border-radius: 1rem 0 0 1rem;
  background: #e8e8e8;
  transition: 0.3s;
}

.search-container button {
  border-radius: 0 1rem 1rem 0;
  margin: 0;
  padding: 10px;
  cursor: pointer;
  border: none;
  background-color: white;
  box-shadow: rgb(0 0 0 / 5%) 0 0 8px;
  transition: all 0.5s ease;
}

.search-container button:hover {
  background-color: hsl(261deg 80% 48%);
  color: hsl(0, 0%, 100%);
  box-shadow: rgb(93 24 220) 0px 7px 29px 0px;
}

.search-container button:active {
  transform: translateY(10px);
  transition: 100ms;
}

ul {
  list-style-type: none;
  padding: 0;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
}

li {
  text-align: center;
  background-color: #f5f5f5;
  padding: 16px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

li:hover {
  transform: translateY(-4px);
}

img {
  max-width: 100%;
  height: auto;
  border-radius: 4px;
}

h1 {
  text-align: center;
  color: #ffffff;
}

a {
  text-decoration: none;
  color: inherit;
}

p {
  margin: 8px 0;
  color: #ffffff;
}

/* Estilos para el botón "Regresar" */
.back-button {
  display: inline-block;
  padding: 8px 16px;
  background-color: #ff9800;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  margin-bottom: 16px;
  text-decoration: none;
}

.back-button:hover {
  background-color: #e68a00;
}


</style>