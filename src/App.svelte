<script>
  let frutas = [
    { nombre: "Manzana roja", emoji: "🍎" },
    { nombre: "Manzana verde", emoji: "🍏" },
    { nombre: "Banana", emoji: "🍌" },
    { nombre: "Uvas", emoji: "🍇" },
    { nombre: "Fresa", emoji: "🍓" },
    { nombre: "Piña", emoji: "🍍" },
    { nombre: "Mango", emoji: "🥭" },
    { nombre: "Durazno", emoji: "🍑" },
    { nombre: "Cerezas", emoji: "🍒" },
    { nombre: "Sandía", emoji: "🍉" },
    { nombre: "Naranja", emoji: "🍊" },
    { nombre: "Limón", emoji: "🍋" },
    { nombre: "Kiwi", emoji: "🥝" },
    { nombre: "Pera", emoji: "🍐" },
    { nombre: "Arándanos", emoji: "🫐" },
    { nombre: "Coco", emoji: "🥥" },
    { nombre: "Melón", emoji: "🍈" },
    { nombre: "Aceituna", emoji: "🫒" },
    { nombre: "Castaña", emoji: "🌰" },
    { nombre: "Tomate", emoji: "🍅" },
  ];

</script>

<div class="row">
  <div class="col">
    <h1 class="text-3xl fw-bold">Recorrer un array en Svelte</h1>
    <ul class="list-group list-group-flush">
      {#each frutas as fruta}
        <li class="list-group-item">{fruta.emoji} {fruta.nombre}</li>
      {/each}
    </ul>
  </div>
</div>

<style>
  li {
    cursor: pointer;
    text-align: start;
  }
</style>
