# Retroalimentación - Proyecto Bento Grid

## Aspectos positivos

1. **Cambio de estructura**: Simplificamos la estructura HTML eliminando divs innecesarios.

2. **Alineación del contenido**: Configuramos `align-items: flex-start` para alinear el contenido a la izquierda.

3. **Tamaño de la imagen**: Redujimos el tamaño de la imagen para que coincidiera con el diseño de referencia.

4. **Cambio de etiqueta**: Cambiamos de `h1` a `h2` para mantener una jerarquía de encabezados más adecuada. (un h1 por página)

5. **Estilos tipográficos**: Añadimos estilos específicos para el texto.

6. **gril-template-columns y grid-template-rows**: especificamos el número de columnas y filas que deseamos en la cuadrícula.

7. **grid-row y grid-column**: especificamos la posición de cada elemento en la cuadrícula.

8. **justify-items**: especificamos la alineación horizontal de los elementos en la cuadrícula.

9.  **gap**: especificamos el espaciado entre los elementos en la cuadrícula.

10. **justify-content**: especificamos la alineación vertical de los elementos en la cuadrícula.
11. **display:flex** : especificamos que el contenedor sea un flexbox.

12. **flex-direction**: especificamos la dirección del flujo de los elementos en el contenedor.

Los cambios principales fueron:

1. **Cambio de estructura**: Simplificamos la estructura HTML eliminando divs innecesarios.

2. **Alineación del contenido**: Configuramos `align-items: flex-start` para alinear el contenido a la izquierda.

3. **Tamaño de la imagen**: Redujimos el tamaño de la imagen para que coincidiera con el diseño de referencia.

4. **Cambio de etiqueta**: Cambiamos de `h1` a `h2` para mantener una jerarquía de encabezados más adecuada. (un h1 por página)


### 2. Mejora en la estructura HTML

Cambiamos la estructura de la tarjeta "Multiple Platforms" de `<div>` anidados a un `<article>` con elementos directos para mejorar la semántica y simplificar el código:

```html
<!-- Antes -->
<div class="multiple-platforms-container">
  <div class="multiple-platforms-image">  <!-- Div innecesario -->
    <img src="./assets/images/illustration-multiple-platforms.webp" alt="" />
  </div>
  <div class="multiple-platforms-text-01">  <!-- Div innecesario -->
    <h1>Manage multiple accounts and platforms.</h1>
  </div>
</div>

<!-- Después -->
<article class="multiple-platforms-container">
  <img src="./assets/images/illustration-multiple-platforms.webp" alt="Iconos de redes sociales" />
  <h2>Manage multiple accounts and platforms.</h2>
</article>
```