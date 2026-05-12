# Evidencia de Aprendizaje: Sitio Web Informativo Institucional

## Objetivo del Proyecto
El objetivo principal de este proyecto es diseñar y desarrollar un sitio web informativo estático para la Fundación Educativa "SmartCampus". La solución busca dotar a la institución de presencia digital utilizando exclusivamente tecnologías del lado del cliente, garantizando una navegación accesible, rápida y una estructura de código semántica.

## Tecnologías Utilizadas
* **HTML5:** Utilizado para estructurar semánticamente el contenido del sitio web (encabezados, párrafos, listas y enlaces).
* **CSS3:** Empleado para la capa de presentación. Se utilizó el modelo `Flexbox` para asegurar que el contenido se distribuya y centre correctamente en el navegador, además de definir la paleta de colores institucionales y la tipografía.
* **Markdown:** Utilizado para la creación de este archivo de documentación técnica.

## Estructura de Archivos
El proyecto está contenido en una carpeta principal e incluye los siguientes archivos:
1. `index.html`: Contiene la estructura de la página de inicio, mostrando la misión, visión y una imagen representativa.
2. `servicios.html`: Presenta una lista organizada de los servicios académicos y cursos que ofrece la institución.
3. `contacto.html`: Despliega la información de contacto (dirección, teléfono y correo electrónico) de forma clara.
4. `style.css`: Hoja de estilos en cascada que controla el diseño visual, los colores, los márgenes y la estructura Flexbox de todas las páginas HTML.
5. `readme.md`: Archivo de documentación actual.

## Explicación de las Secciones Principales
El sitio web está diseñado con un enfoque modular y consistente en sus tres páginas:
* **Encabezado (`<header>`):** Presente en todas las páginas, identifica el nombre de la institución.
* **Navegación (`<nav>`):** Un menú horizontal estilizado con CSS que permite al usuario saltar fácilmente entre Inicio, Servicios y Contacto.
* **Contenedor Principal (`<main>`):** El núcleo de cada página. Utiliza `display: flex` en CSS para agrupar las secciones de información (`<section>`) en un diseño de cuadrícula flexible, permitiendo que el texto y las imágenes se alineen de manera estética y profesional.
* **Pie de Página (`<footer>`):** Cierra el sitio con la información de derechos de autor.