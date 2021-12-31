<template>
  <div id="app">
    <h2>Boton Default</h2>
    <Boton>Default</Boton><br />
    <h2>Outlined</h2>
    <Boton outlined>Default</Boton><br />
    <h2>Tipo text</h2>
    <Boton text>Default</Boton><br />
    <h2>Sin sombra</h2>
    <Boton disableShadow>Default</Boton><br />
    <h2>Boton desabilitado y desabilitado en tipo text</h2>
    <Boton disabled>Default</Boton> <Boton disabled text>Default</Boton><br />
    <h2>Icono al inicio o al final del boton</h2>
    <Boton start>Default</Boton> <Boton end>Default</Boton><br />
    <h2>Tamaño pequeño, mediano y grande</h2>
    <Boton sm>Default</Boton> <Boton md>Default</Boton> <Boton lg>Default</Boton
    ><br />
    <h2>Boton primario, secundario y danger</h2>
    <Boton primary md>Default</Boton> <Boton secondary md>Default</Boton>
    <Boton danger md>Default</Boton><br />
    <link
      href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"
    />
  </div>
</template>

<script src="https://kit.fontawesome.com/89ac75cebc.js" crossorigin="anonymous"></script>
<script>
import Boton from "@/components/Boton.vue";
export default {
  name: "Home",
  components: {
    Boton,
  },
}; 
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
.btn {
  margin: 10px;
}
h2 {
  margin: 20px;
}
div {
  margin: 30px;
}
</style>
