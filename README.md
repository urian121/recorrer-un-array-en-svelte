# Recorrer un array en Svelte

En Svelte, **`{#each}`** no es un método ni una función, sino una estructura de control declarativa que forma parte del lenguaje de plantillas de Svelte.
Es similar a un bucle **`for`** en JavaScript, pero se utiliza dentro de los archivos `.svelte` para iterar sobre arrays y renderizar contenido dinámico en el DOM.


## Resultado final 😀

![Contador con Svelte](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/refs/heads/master/recorrer-array-en-svelte.png)


## ¿Cómo funciona?

- **`{#each}`** recorre un array o cualquier iterable y genera contenido para cada elemento.
- Al renderizar, Svelte optimiza el proceso para minimizar los cambios en el DOM, actualizando solo los elementos que se modifican.

**Ejemplo básico**
<script>
    let numeros = [1, 2, 3, 4, 5];
</script>

```bash
<ul>
    {#each numeros as numero}
        <li>{numero}</li>
    {/each}
</ul>
```

> [!IMPORTANT]
> En resumen, **`{#each}`** es una directiva del lenguaje de plantillas de Svelte, diseñada para iterar y renderizar contenido dinámico de manera declarativa.


```bash
Comenta a otros sobre este proyecto 📢
Invita una cerveza 🍺 o un café ☕
Paypal iamdeveloper86@gmail.com
Da las gracias públicamente 🤓.
```

## No olvides SUSCRIBIRTE 👍
