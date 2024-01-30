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

### UX con metaetiquetas

En el desarrollo web avanzado, se comprendió cómo las metaetiquetas, específicamente a través del Protocolo Open Graph, desempeñan un papel crucial en la mejora de la experiencia del usuario al compartir contenido en redes sociales. Estas metaetiquetas se incorporan en el elemento head del documento HTML, utilizando el atributo property para definir el nombre de los metadatos. Las propiedades esenciales, como título, tipo, URL e imagen, son fundamentales para crear vistas previas efectivas de los enlaces compartidos. Además, se exploraron propiedades opcionales que permiten una descripción más detallada de la página. La implementación adecuada de estas metaetiquetas se traduce en previsualizaciones informativas y atractivas, aumentando la probabilidad de obtener más clics cuando se comparten páginas web en redes sociales.

1. **Metaetiquetas y previsualización en redes sociales:**
   - Las redes sociales generan vistas previas de enlaces compartidos para informar a los usuarios sobre el contenido antes de hacer clic.
   - El uso estratégico de metaetiquetas, específicamente del Protocolo Open Graph, es esencial para controlar qué información se muestra en estas previsualizaciones.

2. **Protocolo Open Graph y metadatos:**
   - Facebook introdujo el Protocolo Open Graph en 2010 para abordar el desafío de mostrar información sobre un sitio web antes de que un usuario haga clic en el enlace.
   - Las metaetiquetas del Protocolo Open Graph se añaden al elemento head del documento HTML, utilizando el atributo property en lugar de name para definir el nombre de los metadatos.
   - Cuatro propiedades esenciales del Protocolo Open Graph: título, tipo, URL e imagen. Estas propiedades permiten a las plataformas de redes sociales crear vistas previas efectivas del enlace compartido.

3. **Propiedades del protocolo Open Graph:**
   - **Título (og:title):** Define el título de la página, visible en la vista previa.
   - **Tipo (og:type):** Especifica el tipo de contenido, como sitio web, vídeo, música o artículo.
   - **URL (og:url):** Define la dirección web permanente de la página específica.
   - **Imagen (og:image):** Especifica la URL de la imagen a mostrar cuando se comparte el sitio web.

4. **Propiedades opcionales del protocolo Open Graph:**
   - Propiedades como descripción, locale (idioma y territorio) y site name (nombre del sitio web) ofrecen información adicional sobre la página.

**Ejemplos:**
```html
<head>
    <!-- Propiedades esenciales del Protocolo Open Graph -->
    <meta property="og:title" content="Título de la Página">
    <meta property="og:type" content="website">
    <meta property="og:url" content="URL de la Página">
    <meta property="og:image" content="URL de la Imagen">

    <!-- Propiedades opcionales -->
    <meta property="og:description" content="Descripción de la Página">
    <meta property="og:locale" content="en_US">
    <meta property="og:site_name" content="Nombre del Sitio">
</head>
```
## Entrada de usuarios y formularios

### Formularios y validación

Los formularios en HTML son elementos cruciales para interactuar con los usuarios y capturar información. Se utilizan comúnmente en situaciones como registros de cuentas, compras en línea o cualquier otro escenario que requiera la entrada de datos del usuario. Para crear un formulario básico en HTML, se utiliza el elemento `<form>`, que puede contener diversos elementos de entrada, botones y otros elementos relacionados con la captura de datos.

**Ejemplo de código:**

```html
<form action="/procesar_formulario" method="post">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" required>

    <label for="email">Correo electrónico:</label>
    <input type="email" id="email" name="email" required>

    <input type="submit" value="Enviar">
</form>
```

En este ejemplo, se crea un formulario básico con campos de entrada para el nombre y el correo electrónico. El atributo `required` indica que estos campos deben ser completados antes de enviar el formulario. Al presionar el botón "Enviar", los datos se enviarán al servidor, donde pueden ser procesados.

**Validación de formularios:**

La validación de formularios es un proceso esencial para asegurarse de que los datos ingresados por los usuarios sean válidos y cumplan con las reglas definidas por el desarrollador. Existen dos enfoques principales: la validación del lado del cliente y la validación del lado del servidor.

- **Validación del lado del cliente:**

    Este método implica la verificación de errores tan pronto como el usuario ingresa datos en el formulario. El navegador web o JavaScript se encargan de este proceso, proporcionando retroalimentación inmediata al usuario.

**Ejemplo de código:**

```html
<input type="email" id="email" name="email" required>
```

En este caso, se utiliza el atributo `type="email"` para validar que el contenido ingresado sea una dirección de correo electrónico válida. Además, el atributo `required` asegura que este campo no se deje en blanco.

- **Validación del Lado del Servidor:**

    Este enfoque verifica los datos después de que son enviados al servidor web, lo que brinda una capa adicional de seguridad contra manipulaciones malintencionadas. En este caso, la validación puede incluir comprobaciones más complejas, como la verificación en una base de datos o la validación con requisitos comerciales específicos.

Ambos métodos de validación se utilizan de manera complementaria para proporcionar una experiencia de usuario fluida y garantizar la integridad de los datos. La combinación de atributos HTML y lógica del lado del servidor permite crear formularios robustos y seguros en aplicaciones web.

### TIpos de entrada

1. **Archivo:**
    - Muestra un control que permite al usuario seleccionar y cargar un archivo desde su ordenador.
      ```html
      <label for="myfile">Select a file:</label>
      <input type="file" id="myfile" name="myfile">
      ```

2. **Oculto:**
    - Define un control que no se muestra pero cuyo valor se sigue enviando al servidor.
      ```html
      <input type="hidden" id="custId" name="custId" value="3487">
      ```

3. **Imagen:**
    - Define una imagen como botón gráfico de envío. Utiliza el atributo "src" para señalar la ubicación de su archivo de imagen.
      ```html
      <input type="image" src="submit_img.png" alt="Submit" width="48" height="48">
      ```

4. **Número:**
    - Define un control para introducir un número con restricciones opcionales, como valores mínimo y máximo permitidos.
      ```html
      <input type="number" id="quantity" name="quantity" min="1" max="5">
      ```

5. **Rango:**
    - Muestra un widget de rango para especificar un número entre dos valores. Puede ser representado por un control deslizante o un dial.
      ```html
      <label for="volume">Volume:</label>
      <input type="range" id="volume" name="volume" min="0" max="10">
      ```

6. **Restablecer:**
    - Muestra un botón que restablece el contenido del formulario a sus valores por defecto.
      ```html
      <input type="reset">
      ```

7. **Buscar:**
    - Define un campo de texto para introducir una consulta de búsqueda.
      ```html
      <label for="gsearch">Search in Google:</label>
      <input type="search" id="gsearch" name="gsearch">
      ```

8. **Hora:**
    - Muestra un control para introducir un valor horario en horas y minutos, sin zona horaria.
      ```html
      <label for="appt">Select a time:</label>
      <input type="time" id="appt" name="appt">
      ```

9. **Tel:**
    - Define un control para introducir un número de teléfono, con opción de validación mediante el atributo "patrón".
      ```html
      <label for="phone">Enter your phone number:</label>
      <input type="tel" id="phone" name="phone" pattern="[+]{1}[0-9]{11,14}">
      ```

10. **URL:**
    - Muestra un campo para introducir una URL de texto con validación automática antes de enviar al servidor.
      ```html
      <label for="homepage">Add your homepage:</label>
      <input type="url" id="homepage" name="homepage">
      ```

11. **Semana:**
    - Define un control para introducir una fecha consistente en un número de semana-año y un año, sin zona horaria.
      ```html
      <label for="week">Select a week:</label>
      <input type="week" id="week" name="week">
      ```

12. **Mes:**
    - Muestra un control para introducir un mes y un año, sin zona horaria.
      ```html
      <label for="bdaymonth">Birthday (month and year):</label>
      <input type="month" id="bdaymonth" name="bdaymonth" min="1930-01" value="2000-01">
      ```

Estos ejemplos cubren una variedad de tipos de entrada en HTML, permitiendo a los desarrolladores construir formularios interactivos y personalizados según sus necesidades específicas. La elección del tipo de entrada dependerá del tipo de datos que se espera y del comportamiento deseado en la interfaz de usuario.

### Creación de un formulario

Para poner en contexto, un restaurante busca ampliar sus servicios permitiendo a los clientes realizar pedidos en línea y recibir comida a domicilio. Para ello, se requiere que los usuarios configuren una cuenta en su sitio web. En este proceso, aprenderemos a crear un formulario de registro simple utilizando HTML. 

#### Estructura Básica del Documento HTML

Se crea un archivo llamado `signup.html` con la estructura básica del documento HTML. Se inicia añadiendo el elemento de formulario, fundamental para recopilar datos del usuario de manera segura. Se configura el atributo `method` a `post` para garantizar el envío seguro de la información.

```html
<form action="#" method="post">
    <!-- Campos del formulario se agregarán aquí -->
</form>
```

#### Campos del Formulario

El formulario debe recopilar información esencial del cliente, como nombre, apellido, dirección de correo electrónico y contraseña. Se crearán campos de entrada para estos datos.

1. **Nombre de Pila:**
   ```html
   <div>
       <label for="user_first_name">Nombre de Pila:</label>
       <input type="text" id="user_first_name" name="user_first_name">
   </div>
   ```

2. **Apellido:**
   ```html
   <div>
       <label for="user_last_name">Apellido:</label>
       <input type="text" id="user_last_name" name="user_last_name">
   </div>
   ```

3. **Correo Electrónico:**
   ```html
   <div>
       <label for="user_email">Correo Electrónico:</label>
       <input type="email" id="user_email" name="user_email">
   </div>
   ```

4. **Contraseña:**
   ```html
   <div>
       <label for="user_password">Contraseña:</label>
       <input type="password" id="user_password" name="user_password">
   </div>
   ```

5. **Confirmar Contraseña:**
   ```html
   <div>
       <label for="user_confirm_password">Confirmar Contraseña:</label>
       <input type="password" id="user_confirm_password" name="user_confirm_password">
   </div>
   ```

#### Asociación de etiquetas y mejora de la experiencia del usuario

Cada campo de entrada se asocia con una etiqueta para mejorar la experiencia del usuario y facilitar la comprensión del formulario. Además, se añade un salto de línea después de cada etiqueta para una presentación ordenada.

```html
<label for="user_first_name">Nombre de Pila:</label>
<input type="text" id="user_first_name" name="user_first_name"><br>
```

#### Botón de envío

Finalmente, se agrega un botón de envío dentro del último elemento `<div>`. Este botón se utilizará para enviar los datos del formulario al backend.

```html
<div>
    <button type="submit">Sign Up</button>
</div>
```

En este proceso, se ha aprendido a crear un formulario básico de registro para el sitio web. Se destacan elementos cruciales como el uso del atributo `method` para una transmisión segura, la asociación de etiquetas para mejorar la experiencia del usuario y la implementación de campos de entrada para recopilar información esencial. Este formulario proporcionará la base para que los usuarios configuren sus cuentas, marcando un paso importante para la expansión de los servicios de entrega en línea del restaurante.

### Botones de Radio en Formularios HTML: Explorando y Creando

La comodidad de reservar servicios en línea ha llevado al restaurante mencionado anteriormente a implementar un sistema de reserva de mesas en su sitio web. Para lograrlo, se utilizarán botones de radio en un formulario HTML, permitiendo a los clientes elegir entre diferentes tamaños de mesa y ubicaciones. Veamos cómo configurar este formulario y proporcionar una experiencia de usuario mejorada.

#### Estructura básica del documento HTML

Se crea un nuevo archivo llamado `booking.html` con la estructura HTML básica. Se inicia añadiendo un elemento de formulario que contendrá botones de radio para seleccionar el tamaño de la mesa y la ubicación.

```html
<form action="#" method="post">
    <fieldset id="size">
        <!-- Botones de radio para el tamaño de la mesa se agregarán aquí -->
    </fieldset>

    <fieldset id="location">
        <!-- Botones de radio para la ubicación se agregarán aquí -->
    </fieldset>

    <button type="submit">Book</button>
</form>
```

#### Botones de radio para tamaño de mesa

Dentro del primer `fieldset`, se añaden botones de radio para representar los diferentes tamaños de mesa disponibles (para dos personas, cuatro personas y seis personas).

```html
<input type="radio" id="two" name="size" value="2">
<label for="two">Two-person table</label>

<input type="radio" id="four" name="size" value="4" checked>
<label for="four">Four-person table</label>

<input type="radio" id="six" name="size" value="6">
<label for="six">Six-person table</label>
```

#### Botones de radio para ubicación

Dentro del segundo `fieldset`, se añaden botones de radio para seleccionar la ubicación de la mesa (interior o exterior).

```html
<input type="radio" id="indoor" name="location" value="interior" checked>
<label for="indoor">Indoor</label>

<input type="radio" id="outdoor" name="location" value="outdoors">
<label for="outdoor">Outdoors</label>
```

#### Mejora de la experiencia del usuario en dispositivos móviles

Para mejorar la experiencia en dispositivos móviles, se envuelven los textos y los botones de radio en elementos de etiqueta. Esto facilita la selección al hacer clic en el texto.

```html
<label for="two">Two-person table<input type="radio" id="two" name="size" value="2"></label>
```

El formulario de reserva de mesas se ha configurado con éxito utilizando botones de radio. Cada grupo de botones (tamaño y ubicación) está encapsulado en su propio `fieldset`, proporcionando claridad y estructura al formulario. La selección de un tamaño de mesa o ubicación anulará la elección previa, ya que los botones de radio permiten elegir solo una opción de cada grupo. Además, se implementa una mejora para dispositivos móviles al envolver los textos y botones en elementos de etiqueta, facilitando la selección en pantallas más pequeñas.

