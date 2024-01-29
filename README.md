# INTRODUCCIÓN A HTML Y CSS

## Semántica y metaetiquetas

### Etiquetas semánticas

En HTML, la descripción del contenido de una página web no solo se trata de su apariencia, sino también de su significado. Para ello, se utilizan etiquetas semánticas que aportan contexto y facilitan la comprensión del contenido tanto a los motores de búsqueda como a los lectores de pantalla. Estas etiquetas ayudan a estructurar la información de manera lógica y comprensible.

**Estructura básica de una página HTML**

La estructura básica de una página HTML incluye el encabezado (`<head>`) y el cuerpo (`<body>`). Sin embargo, para una descripción semántica más profunda, se pueden utilizar etiquetas específicas para distintas secciones de la página.

**Elementos semánticos principales**

1. **header**: Utilizado para la cabecera de la página, puede contener elementos como el logotipo y enlaces de navegación.

    ```html
    <header>
        <img src="logo.png" alt="Logo de la empresa">
        <nav>
            <a href="#">Inicio</a>
            <a href="#">Servicios</a>
            <a href="#">Contacto</a>
        </nav>
    </header>
    ```

2. **nav**: Describe la sección de navegación principal de la página.

    ```html
    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Productos</a></li>
            <li><a href="#">Contacto</a></li>
        </ul>
    </nav>
    ```

3. **main**: Representa el contenido principal de la página.

    ```html
    <main>
        <!-- Contenido principal aquí -->
    </main>
    ```

4. **footer**: Utilizado para el pie de página, que puede contener información de contacto y enlaces a redes sociales.

    ```html
    <footer>
        <p>Contacto: info@example.com</p>
        <ul>
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">LinkedIn</a></li>
        </ul>
    </footer>
    ```

**Elementos semánticos para el contenido principal**

1. **article**: Indica contenido autocontenible, como un artículo de blog.

    ```html
    <article>
        <header>
            <h2>Título del Blog</h2>
            <p>Fecha: 01 de enero de 2023</p>
        </header>
        <p>Contenido del artículo...</p>
    </article>
    ```

2. **section**: Permite definir secciones individuales dentro de un artículo.

    ```html
    <article>
        <section>
            <h3>Sección 1</h3>
            <p>Contenido de la sección...</p>
        </section>
        <section>
            <h3>Sección 2</h3>
            <p>Otro contenido de la sección...</p>
        </section>
    </article>

    ```

Estos elementos semánticos no están limitados a una estructura fija y pueden anidarse según la necesidad, permitiendo una descripción precisa del contenido y mejorando la accesibilidad de la página web.

### Etiquetas de seccionamiento

El seccionamiento en HTML permite organizar un documento de manera estructurada, facilitando la comprensión del contenido. Aquí se presentan algunas etiquetas clave de seccionamiento:

1. **`<header>`: Cabecera de la página web**
   - Utilizada para la cabecera de una sección o de toda la página web.
   - Contiene elementos como el logotipo o la marca del sitio.
   ```html
   <header>
       <img src="logo.png" alt="Logo del Sitio">
       <h1>Nombre del Sitio</h1>
   </header>
   ```

2. **`<nav>`: Enlaces de navegación**
   - Reservada para los enlaces de navegación de una sección o de la página web.
   ```html
   <nav>
       <a href="#">Inicio</a>
       <a href="#">Productos</a>
       <a href="#">Contacto</a>
   </nav>
   ```

3. **`<footer>`: Pie de página**
   - Representa el pie de página de una sección o de la página web.
   - Contiene información como enlaces secundarios, aviso de copyright y políticas.
   ```html
   <footer>
       <p>&copy; 2024 Nombre del Sitio</p>
       <a href="#">Política de Privacidad</a>
   </footer>
   ```

4. **`<main>`: Contenido principal**
   - Especifica el contenido principal de una sección o de la página web.
   ```html
   <main>
       <h2>Últimas Noticias</h2>
       <p>Contenido principal...</p>
   </main>
   ```

5. **`<aside>`: Contenidos secundarios**
   - Conjunto de contenidos secundarios no esenciales para comprender el contenido principal.
   ```html
   <aside>
       <h3>Publicidad</h3>
       <p>Anuncio aquí...</p>
   </aside>
   ```

6. **`<article>`: Bloque de contenido independiente**
   - Representa un bloque de contenido independiente y autónomo, como una entrada de blog.
   ```html
   <article>
       <h3>Título del Artículo</h3>
       <p>Contenido del artículo...</p>
   </article>
   ```

7. **`<section>`: Sección independiente**
   - Utilizada para definir una sección independiente del documento.
   ```html
   <section>
       <h2>Sección 1</h2>
       <p>Contenido de la sección...</p>
   </section>
   ```

8. **`<details>` y `<summary>`: Contenido colapsable**
   - `<details>` define una sección colapsada de contenido.
   - `<summary>` especifica el resumen o pie de foto de ese contenido.
   ```html
   <details>
       <summary>Detalles</summary>
       <p>Contenido colapsable...</p>
   </details>
   ```

9. **Encabezados `<h1>` a `<h6>`: Encabezamientos de la página web**
   - Indican el nivel de importancia del encabezado, desde el más importante `<h1>` hasta el menos importante `<h6>`.
   ```html
   <h1>Encabezado Principal</h1>
   <h2>Subencabezado</h2>
   ```

El seccionamiento en HTML es esencial para estructurar una página web de manera clara y significativa. Cada etiqueta tiene un propósito específico: `<header>` para la cabecera, `<nav>` para la navegación, `<footer>` para el pie de página, `<main>` para el contenido principal, `<aside>` para contenidos secundarios, `<article>` para bloques de contenido independientes, `<section>` para secciones independientes, y `<details>` y `<summary>` para contenido colapsable. Los encabezados `<h1>` a `<h6>` agregan jerarquía y significado al texto.

### Etiquetas de contenido 

Las etiquetas de contenido en HTML permiten estructurar y presentar diferentes tipos de información de manera significativa. A continuación, se presentan algunas etiquetas de contenido clave:

1. **`<blockquote>`: Cita**
   - Se utiliza para describir una cita en el documento.
   ```html
   <blockquote>
       Esta es una cita relevante en el contexto del documento.
   </blockquote>
   ```

2. **`<dd>` y `<dt>`: Lista de descripción**
   - `<dd>` se utiliza para definir una descripción para el elemento `<dt>` precedente.
   - `<dt>` se utiliza para describir términos dentro de los elementos `<dl>` (lista de descripción).
   ```html
   <dl>
       <dt>Término 1</dt>
       <dd>Definición de Término 1</dd>
       <dt>Término 2</dt>
       <dd>Definición de Término 2</dd>
   </dl>
   ```

3. **`<figcaption>` y `<figure>`: Pie de foto e imagen fotográfica**
   - `<figcaption>` define un pie de foto para una imagen fotográfica.
   - `<figure>` se utiliza para aplicar marcas a una imagen fotográfica.
   ```html
   <figure>
       <img src="imagen.jpg" alt="Descripción de la imagen">
       <figcaption>Pie de foto para la imagen</figcaption>
   </figure>
   ```

4. **`<hr>`: Línea horizontal**
   - Añade una línea horizontal al elemento padre.
   ```html
   <p>Texto antes de la línea horizontal</p>
   <hr>
   <p>Texto después de la línea horizontal</p>
   ```

5. **`<li>`: Elemento de lista**
   - Se utiliza para definir un elemento dentro de una lista (ya sea ordenada o desordenada).
   ```html
   <ul>
       <li>Elemento 1</li>
       <li>Elemento 2</li>
   </ul>
   ```

6. **`<menu>`: Alternativa semántica a `<ul>`**
   - Proporciona una alternativa semántica a la etiqueta `<ul>`.
   ```html
   <menu>
       <li>Elemento 1</li>
       <li>Elemento 2</li>
   </menu>
   ```

7. **`<ol>`: Lista ordenada**
   - Define una lista ordenada.
   ```html
   <ol>
       <li>Primer elemento</li>
       <li>Segundo elemento</li>
   </ol>
   ```

8. **`<p>`: Párrafo**
   - Define un párrafo.
   ```html
   <p>Este es un párrafo de texto.</p>
   ```

9. **`<pre>`: Texto preformateado**
   - Se utiliza para representar texto preformateado con fuente monoespaciada.
   ```html
   <pre>
       Esto
       es
       texto
       preformateado.
   </pre>
   ```

10. **`<ul>`: Lista desordenada**
    - Define una lista desordenada.
    ```html
    <ul>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
    </ul>
    ```

Las etiquetas de contenido en HTML desempeñan un papel crucial al organizar y estructurar información en una página web. Desde la definición de citas y listas de descripción hasta la inclusión de imágenes con pies de foto, estas etiquetas proporcionan una forma semántica de presentar diversos tipos de contenido. Además, las etiquetas como `<hr>` y `<p>` ayudan a mejorar la legibilidad y presentación del texto en el documento. 

### Etiquetas en línea

Las etiquetas en línea en HTML se utilizan para aplicar estilos y significado a partes específicas del texto en un documento. Aquí se presentan algunas etiquetas en línea esenciales:

1. **`<a>`: Enlace de anclaje**
   - Se utiliza para crear un enlace de anclaje a otro documento HTML.
   ```html
   <a href="pagina.html">Enlace a otra página</a>
   ```

2. **`<abbr>`: Abreviatura o acrónimo**
   - Especifica que el texto que contiene es una abreviatura o acrónimo.
   ```html
   <p>La <abbr title="Organización de las Naciones Unidas">ONU</abbr> es una organización internacional.</p>
   ```

3. **`<b>`: Texto en negrita**
   - Pone en negrita el texto que contiene. Se prefiere `<strong>` para indicar importancia.
   ```html
   <p><b>Texto en negrita</b></p>
   ```

4. **`<br>`: Salto de línea**
   - Crea un salto de línea, moviendo el texto subsiguiente a una nueva línea.
   ```html
   <p>Este es un texto.<br>Nueva línea aquí.</p>
   ```

5. **`<cite>`: Título de una obra creativa**
   - Define el título de una obra creativa, como un libro o una película.
   ```html
   <cite>El gran Gatsby</cite> es una novela clásica.
   ```

6. **`<code>`: Bloque de código informático**
   - Indica que el texto que contiene es un bloque de código informático.
   ```html
   <code>function ejemplo() { return "Hola mundo"; }</code>
   ```

7. **`<data>`: Datos legibles por máquina**
   - Indica datos legibles por máquina.
   ```html
   <p>Peso: <data value="75">75</data> kg</p>
   ```

8. **`<em>`: Enfatizar texto**
   - Enfatiza el texto que contiene.
   ```html
   <p><em>Texto enfatizado</em></p>
   ```

9. **`<i>`: Texto en cursiva**
   - El texto que contiene aparece en cursiva, se utiliza para indicar texto idiomático o términos técnicos.
   ```html
   <p><i>Texto en cursiva</i></p>
   ```

10. **`<mark>`: Texto marcado o resaltado**
    - El texto que contiene debe marcarse o resaltarse.
    ```html
    <p>Este es un <mark>texto resaltado</mark>.</p>
    ```

11. **`<q>`: Cita corta**
    - El texto que contiene es una cita corta.
    ```html
    <p><q>Texto de la cita corta</q></p>
    ```

12. **`<s>`: Texto tachado**
    - Muestra el texto que contiene con un tachado o una línea que lo atraviesa.
    ```html
    <p><s>Texto tachado</s></p>
    ```

13. **`<samp>`: Muestra de texto**
    - El texto que contiene representa una muestra.
    ```html
    <p>Resultado: <samp>10</samp></p>
    ```

14. **`<small>`: Texto de pequeño tamaño**
    - Se utiliza para representar texto de pequeño tamaño, como derechos de autor.
    ```html
    <small>&copy; 2022 Mi Empresa</small>
    ```

15. **`<span>`: Elemento genérico para estilo CSS**
    - Un elemento genérico para agrupar contenido para el estilo CSS.
    ```html
    <p>Este es un <span style="color: red;">texto con estilo</span>.</p>
    ```

16. **`<strong>`: Texto en negrita para indicar importancia**
    - Muestra el texto que contiene en negrita y se utiliza para indicar importancia.
    ```html
    <p><strong>Importante:</strong> Este mensaje requiere atención.</p>
    ```

17. **`<sub>` y `<sup>`: Texto subíndice y superíndice**
    - `<sub>` muestra el texto con una línea de base rebajada, `<sup>` con una línea de base elevada.
    ```html
    <p>H<sub>2</sub>O es agua. 10<sup>2</sup> es 100.</p>
    ```

18. **`<time>`: Etiqueta semántica para fechas y horas**
    - Se utiliza para mostrar tanto fechas como horas.
    ```html
    <p>La reunión está programada para <time datetime="2022-01-15T18:30">hoy a las 6:30 PM</time>.</p>
    ```

19. **`<u>`: Texto subrayado**
    - Muestra el texto que contiene con un subrayado sólido.
    ```html
    <p><u>Texto subrayado</u></p>
    ```

20. **`<var>`: Variable en una expresión matemática**
    - El texto contenedor es una variable en una expresión matemática.
    ```html
    <p>La fórmula es: <var>x</var> + 2 = 8</p>
    ```

Las etiquetas en línea en HTML son esenciales para aplicar formato y significado a partes específicas del contenido en un documento. Desde la creación de enlaces (`<a>`) hasta la indicación de texto importante (`<strong>`) o la representación de datos legibles por máquina (`<data>`), estas etiquetas ofrecen flexibilidad y semántica al desarrollo web. Al entender y utilizar adecuadamente estas etiquetas, los desarrolladores pueden mejorar la legibilidad y la accesibilidad de sus páginas web. Además, permiten la aplicación de estilos específicos a partes individuales del contenido, lo que contribuye a una presentación efectiva y atractiva del texto.

### Contenido incrustado y etiquetas multimedia en HTML

Las etiquetas multimedia en HTML permiten la inclusión de contenido enriquecido, como audio, video e imágenes, proporcionando una experiencia más interactiva y atractiva para los usuarios. Aquí se presentan algunas etiquetas clave:

1. **`<audio>`: Incrustar audio**
   - Se utiliza para incrustar archivos de audio en las páginas web.
   ```html
   <audio controls>
     <source src="cancion.mp3" type="audio/mp3">
     Tu navegador no soporta el elemento de audio.
   </audio>
   ```

2. **`<canvas>`: Gráficos 2D y 3D**
   - Se utilizan para representar gráficos 2D y 3D en las páginas web.
   ```html
   <canvas width="300" height="200"></canvas>
   ```

3. **`<embed>`: Contenidos externos**
   - Se utiliza como elemento contenedor de contenidos externos proporcionados por una aplicación externa.
   ```html
   <embed type="application/pdf" src="documento.pdf" width="500" height="400">
   ```

4. **`<iframe>`: Incrustar páginas web anidadas**
   - Se utiliza para incrustar una página web anidada dentro de otra.
   ```html
   <iframe src="pagina.html" width="600" height="400"></iframe>
   ```

5. **`<img>`: Incrustar imagen**
   - Incrusta una imagen en una página web.
   ```html
   <img src="imagen.jpg" alt="Descripción de la imagen">
   ```

6. **`<object>`: Contenido de complemento del navegador**
   - Similar a `<embed>`, pero el contenido lo proporciona un complemento del navegador web.
   ```html
   <object data="archivo.swf" width="550" height="400"></object>
   ```

7. **`<picture>`: Imágenes responsivas**
   - Elemento que contiene un elemento `<img>` y uno o más elementos `<source>` para ofrecer imágenes alternativas para diferentes pantallas/dispositivos.
   ```html
   <picture>
     <source media="(min-width: 768px)" srcset="imagen-grande.jpg">
     <img src="imagen-pequena.jpg" alt="Descripción de la imagen">
   </picture>
   ```

8. **`<video>`: Incrustar vídeo**
   - Incrusta un vídeo en una página web.
   ```html
   <video controls width="600">
     <source src="video.mp4" type="video/mp4">
     Tu navegador no soporta el elemento de video.
   </video>
   ```

9. **`<source>`: Especificar recursos multimedia**
   - Especifica recursos multimedia para los elementos `<picture>`, `<audio>` y `<video>`.
   ```html
   <video controls>
     <source src="video.mp4" type="video/mp4">
     Tu navegador no soporta el elemento de video.
   </video>
   ```

10. **`<svg>`: Gráficos vectoriales escalables**
    - Se utiliza para definir gráficos vectoriales escalables dentro de una página web.
    ```html
    <svg width="100" height="100">
      <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
    </svg>
    ```

El contenido incrustado y las etiquetas multimedia en HTML son esenciales para enriquecer las páginas web con elementos interactivos. La etiqueta `<audio>` permite la incorporación de archivos de audio con controles de reproducción, mientras que `<video>` hace lo mismo para archivos de vídeo. La etiqueta `<img>` es fundamental para mostrar imágenes, y `<canvas>` proporciona un lienzo para gráficos dinámicos. Para contenido externo, `<iframe>` y `<object>` son útiles, y `<embed>` sirve como contenedor para varios tipos de contenido. La etiqueta `<picture>` facilita la creación de imágenes responsivas. Además, `<svg>` permite la inclusión de gráficos vectoriales escalables. Estas etiquetas ofrecen flexibilidad para crear experiencias web más ricas e interactivas.

### Etiquetas de tabla en HTML

Las etiquetas de tabla en HTML son esenciales para organizar y mostrar datos tabulares de manera estructurada en una página web. Aquí se presentan las etiquetas clave:

1. **`<table>`: Definir una tabla**
   - Define un elemento de tabla para mostrar datos de tabla dentro de una página web.
   ```html
   <table>
     <!-- Contenido de la tabla va aquí -->
   </table>
   ```

2. **`<thead>`: Cabecera de la tabla**
   - Representa el contenido de la cabecera de una tabla y normalmente contiene un elemento `<tr>` (fila).
   ```html
   <thead>
     <tr>
       <th>Encabezado 1</th>
       <th>Encabezado 2</th>
     </tr>
   </thead>
   ```

3. **`<tbody>`: Contenido principal de la tabla**
   - Representa el contenido principal de una tabla y contiene uno o más elementos `<tr>` (filas).
   ```html
   <tbody>
     <tr>
       <td>Dato 1</td>
       <td>Dato 2</td>
     </tr>
     <!-- Otras filas van aquí -->
   </tbody>
   ```

4. **`<tfoot>`: Pie de página de la tabla**
   - Representa el contenido del pie de página de una tabla y normalmente contiene un elemento `<tr>` (fila).
   ```html
   <tfoot>
     <tr>
       <td>Total</td>
       <td>Suma</td>
     </tr>
   </tfoot>
   ```

5. **`<tr>`: Fila de la tabla**
   - Representa una fila de una tabla y contiene uno o más elementos `<td>` (celdas) cuando se utiliza dentro de `<tbody>` o `<tfoot>`. Cuando se utiliza dentro de `<thead>`, contiene uno o más elementos `<th>` (celdas de encabezado).
   ```html
   <tr>
     <td>Dato A</td>
     <td>Dato B</td>
   </tr>
   ```

6. **`<td>`: Celda de la tabla**
   - Representa una celda en una tabla y contiene el contenido de texto de la celda.
   ```html
   <tr>
     <td>Dato 1</td>
     <td>Dato 2</td>
   </tr>
   ```

7. **`<th>`: Celda de encabezado**
   - Define una celda de encabezado de una tabla y contiene el contenido de texto de la cabecera.
   ```html
   <thead>
     <tr>
       <th>Encabezado 1</th>
       <th>Encabezado 2</th>
     </tr>
   </thead>
   ```

8. **`<caption>`: Título de la tabla**
   - Define el título de un elemento de tabla.
   ```html
   <caption>Tabla de Datos</caption>
   <table>
     <!-- Contenido de la tabla va aquí -->
   </table>
   ```

9. **`<colgroup>`: Grupo de columnas**
   - Define un grupo semántico de una o varias columnas de una tabla para su formateo.
   ```html
   <colgroup>
     <col span="2" style="background-color:lightblue">
   </colgroup>
   ```

10. **`<col>`: Columna semántica**
    - Define una columna semántica en una tabla.
    ```html
    <colgroup>
      <col style="background-color:lightblue">
      <col style="background-color:lightgreen">
    </colgroup>
    ```

Las etiquetas de tabla en HTML permiten la creación y presentación de datos tabulares de manera organizada. La etiqueta `<table>` sirve como contenedor principal, mientras que `<thead>`, `<tbody>`, y `<tfoot>` dividen la tabla en secciones de cabecera, contenido principal y pie de página respectivamente. `<tr>` representa filas, `<td>` celdas de datos y `<th>` celdas de encabezado. `<caption>` proporciona un título descriptivo, y `<colgroup>` y `<col>` ofrecen opciones de formateo para columnas. Juntas, estas etiquetas proporcionan una estructura clara y semántica para presentar información tabular en una página web.

### Etiquetas semánticas en acción: Creando una página de blog con HTML

En el proceso de añadir una página de blog al sitio web del restaurante Little Lemon, se ha puesto un fuerte énfasis en la utilización de etiquetas semánticas en HTML. Esto es esencial para mejorar la accesibilidad y facilitar la comprensión del contenido por parte de los motores de búsqueda. Veamos un ejemplo de estructurado de una página:

1. **Estructura Básica:**
   - Se ha establecido la estructura básica del documento HTML, destacando la importancia de la semántica.
   ```html
   <html>
     <head>...</head>
     <body>
       <!-- Elementos semánticos: header, nav, main, footer -->
     </body>
   </html>
   ```

2. **Detalles de Cada Elemento:**
   - Cada elemento (header, nav, main, footer) se ha utilizado con un propósito específico para describir semánticamente el contenido.
   ```html
   <header> <!-- Logo de Little Lemon --> </header>
   <nav> <!-- Enlaces de navegación --> </nav>
   <main> <!-- Contenido principal del blog --> </main>
   <footer> <!-- Información de derechos de autor --> </footer>
   ```

3. **Detalles Adicionales:**
   - Se añaden detalles específicos dentro de cada elemento para enriquecer la semántica.
   ```html
   <!-- Dentro de header -->
   <img src="logo.jpg" alt="Little Lemon Logo">

   <!-- Dentro de nav -->
   <ul>
     <li><a href="index.html">Inicio</a></li>
     <li><a href="location.html">Ubicación</a></li>
     <li><a href="blog.html">Blog</a></li>
   </ul>

   <!-- Dentro de main -->
   <h1>Encabezado del Blog</h1>
   <article>
     <h2>20% de Descuento Este Fin de Semana</h2>
     <p>Texto de la entrada del blog...</p>
   </article>
   <article>
     <h2>Nuestro Nuevo Menú</h2>
     <p>Texto de la entrada del blog...</p>
   </article>

   <!-- Dentro de footer -->
   <p>Aviso de Copyright</p>
   ```

4. **Resultado y Visualización:**
   - Se destaca la importancia de la correcta visualización del contenido, que es posible gracias a la estructura semántica.
   ```html
   <!-- Guardar y previsualizar -->
   ```

### Metadatos

Los metadatos son elementos esenciales en el mundo del desarrollo web, aunque a menudo permanecen invisibles para el usuario promedio. En su esencia, los metadatos son datos sobre otros datos, y en el contexto de las páginas web, desempeñan un papel crucial en la optimización para motores de búsqueda (SEO) y la mejora de la experiencia del usuario.

Las metaetiquetas, o simplemente metadatos, se insertan dentro del elemento principal del documento HTML. Aunque no son visibles en el navegador, son fundamentales para proporcionar información estructurada a los motores de búsqueda y otros sistemas que analizan el contenido de la web. Vamos a explorar algunos ejemplos de código que ilustran cómo se implementan estos metadatos.

```html
<!-- Metaetiqueta de Autor -->
<meta name="author" content="Nombre del Autor - Nombre de la Empresa">

<!-- Metaetiqueta de Descripción -->
<meta name="description" content="Texto descriptivo sobre el contenido de la página">

<!-- Metaetiqueta de Palabras Clave (desaconsejada) -->
<meta name="keywords" content="Palabra clave 1, Palabra clave 2, ...">

<!-- Metaetiqueta de Robots (indicando indexación y seguimiento) -->
<meta name="robots" content="index, follow">
```

En el ejemplo anterior, la metaetiqueta de autor identifica la persona y la empresa detrás de la página. La metaetiqueta de descripción proporciona un resumen descriptivo que los motores de búsqueda suelen utilizar en los resultados de búsqueda. La metaetiqueta de palabras clave, aunque anteriormente utilizada, se desaconseja en la actualidad debido a su abuso en prácticas de manipulación de rankings.

```html
<!-- Metaetiqueta de Puerto de Visualización para Dispositivos Móviles -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

El código anterior representa una metaetiqueta crucial para el diseño web adaptable. Específicamente, controla cómo se visualiza la página en dispositivos móviles, asegurando una experiencia de usuario óptima. El atributo "width=device-width" establece el ancho del dispositivo como el ancho de la pantalla, mientras que "initial-scale=1.0" establece la escala inicial.

### Hoja de datos sobre metadatos

Como anteriormente se mencionó, las etiquetas HTML `<meta>` son elementos fundamentales para transmitir información crucial a los motores de búsqueda y mejorar la categorización de las páginas web. Se tiene una hoja de trucos que resume las características más importantes de estas etiquetas y cómo implementarlas.

**Estructura de la etiqueta Meta:**

```html
<meta name="nombre" content="valor">
```

**Campo "Nombre":**
- El nombre puede ser personalizado, pero se recomienda usar valores comprensibles para los navegadores.
- Ejemplo: `<meta name="author" content="Nombre del Autor">` para indicar el autor.

**Campo "Contenido":**
- Especifica el valor asociado a la propiedad.
- Ejemplo: `<meta name="language" content="english">` para definir el idioma de la página.

**Conjunto de caracteres (Charset):**
```html
<meta charset="UTF-8">
```

**HTTP-equiv (Equivalente HTTP):**
- Utilizado para simular cabeceras de respuesta HTTP.
- Ejemplo: `<meta http-equiv="refresh" content="30">` para actualizar la página cada 30 minutos.

**Metaetiquetas Básicas para SEO:**
```html
<meta name="description"/> <!-- Descripción breve de la página -->
<meta name="title"/> <!-- Título de la página -->
<meta name="author" content="name"/> <!-- Autor de la página -->
<meta name="language" content="english"/> <!-- Idioma de la página -->
<meta name="robots" content="index,follow"/> <!-- Instrucciones a los motores de búsqueda -->
<meta name="google"/> <!-- Instrucción específica para Google -->
<meta name="googlebot" content="notranslate"/> <!-- Inhibir traducción automática en Google -->
<meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm"/> <!-- Fecha de última modificación -->
<meta name="rating" content="safe for kids"/> <!-- Audiencia prevista -->
<meta name="copyright" content="Copyright 2022"/> <!-- Copyright -->

**Metaetiquetas HTTP-equiv:**
```html
<meta http-equiv="content-type" content="text/html"/> <!-- Formato del documento devuelto por el servidor -->
<meta http-equiv="default-style"/> <!-- Formato del documento de estilo -->
<meta http-equiv="refresh"/> <!-- Duración antes de considerar la página obsoleta -->
<meta http-equiv="Content-language"/> <!-- Idioma de la página -->
<meta http-equiv="Cache-Control" content="no-cache"/> <!-- Instrucciones de almacenamiento en caché -->

**Metaetiquetas para Diseño Adaptable/Móvil:**
```html
<meta name="format-detection" content="telephone=yes"/> <!-- Números de teléfono como enlaces -->
<meta name="HandheldFriendly" content="true"/> <!-- Visualización correcta en dispositivos móviles -->
<meta name="viewport" content="width=device-width, initial-scale=1.0"/> <!-- Área de visualización del contenido -->
```

Las etiquetas `<meta>` en HTML permiten a los desarrolladores web comunicar información esencial a los motores de búsqueda y optimizar la presentación de las páginas. El campo "Nombre" identifica la propiedad, mientras que "Contenido" especifica su valor. Por ejemplo, para indicar el autor de una página, se utiliza la etiqueta `<meta name="author" content="Nombre del Autor">`.

Para SEO, las metaetiquetas básicas como `<meta name="description"/>` ofrecen una breve descripción de la página, mientras que `<meta name="robots" content="index,follow"/>` instruye a los motores de búsqueda sobre cómo indexar la página. Las metaetiquetas HTTP-equiv, como `<meta http-equiv="content-type" content="text/html"/>`, definen el formato del documento devuelto por el servidor.

En el ámbito móvil, `<meta name="viewport" content="width=device-width, initial-scale=1.0"/>` es crucial para especificar cómo se visualiza la página en dispositivos móviles. Esta hoja de trucos sirve como referencia práctica para implementar eficazmente metadatos y mejorar la visibilidad y usabilidad de las páginas web.
