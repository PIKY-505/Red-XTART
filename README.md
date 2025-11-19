# 🏫 Web Oficial del Centro XTART

Este repositorio contiene el proyecto desarrollado para el módulo de **Lenguaje de Marcas**. El objetivo es la creación de la página web oficial del **Centro XTART**, aplicando estándares modernos de desarrollo web, etiquetas semánticas y metodologías de organización de estilos.

## 📋 Descripción del Proyecto

El sitio web es completamente estático y ha sido diseñado para ser claro, coherente y navegable. Se ha puesto especial énfasis en la maquetación flexible y la arquitectura CSS escalable.

### 🛠️ Tecnologías y Requisitos Técnicos

El proyecto cumple con las siguientes especificaciones técnicas:

* **HTML5 Semántico:** Uso estricto de etiquetas de estructura (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
* **CSS3:** Estilos definidos en una hoja externa (`style.css`).
* **Metodología BEM:** Nomenclatura de clases estandarizada (Bloque, Elemento, Modificador) para mantener un código limpio (ej. `nav__item`, `card--highlight`).
* **Sistemas de Diseño (Layout):**
    * **Flexbox:** Implementado en menús de navegación, alineación de elementos en el footer y cabeceras.
    * **CSS Grid:** Implementado en galerías de imágenes, distribución de secciones principales y layouts de tarjetas.

## 📂 Estructura del Sitio

La web consta de **4 páginas HTML** enlazadas entre sí:

1.  **`index.html`**: Página principal (Home).
2.  **`centro.html`**: Información institucional del centro.
3.  **`ciclos.html`**: Oferta educativa y ciclos formativos.
4.  **`contacto.html`**: Formulario de contacto y ubicación.

### Estructura de Carpetas
El entregable sigue la siguiente organización de archivos:

```text
/ (raíz del proyecto)
├── html/
│   └──index.html
│   └──centro.html
│   └──ciclos.html
│   └──contacto.html
├── css/
│   └── style.css
└── img/
    └── (imágenes optimizadas con atributos alt)
