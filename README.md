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

