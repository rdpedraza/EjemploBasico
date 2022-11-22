<script>
let contador = 0;
$: total = contador;

function clicks(){
    contador++;
}
</script>
<div class="Boton">
    <button on:click={clicks}>Apretar</button>
    <div>Has dado {total} clicks</div>
</div>
<style>

</style>