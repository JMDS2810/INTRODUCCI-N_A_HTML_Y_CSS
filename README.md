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


