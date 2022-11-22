<script>
  let nombre = 'Diego';
  import Boton from "./componentes/Boton.svelte";
</script>

<main>
  <h1>Escribe tu nombre</h1> 
  <input type="text" bind:value={nombre}>
  <p>Hola, {nombre}!</p>

  <Boton />
</main>

<style>

</style>
