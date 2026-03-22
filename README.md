# BlogdeCafé

Sitio web multipágina estático de un blog de café, creado con HTML y CSS puro. Cada página tiene su propia sección de contenido, diseño responsivo y una estructura visual organizada que le da dinamismo al sitio sin depender de frameworks.

**Demo en vivo:** [blog-cafe-sebas.netlify.app](https://blog-cafe-sebas.netlify.app/)
<img width="1437" height="870" alt="image" src="https://github.com/user-attachments/assets/d2633417-7bf0-4ab7-ab52-15bba65253b2" />


## Páginas incluidas

- **index.html** — Página principal con blog de entradas y sidebar de cursos
- **nosotros.html** — Sección sobre el equipo
- **cursos.html** — Listado de cursos y talleres disponibles
- **contacto.html** — Formulario de contacto con imagen de fondo
- **entrada.html** — Página individual de entrada de blog

## Tecnologías utilizadas

- HTML5
- CSS3 (Custom Properties, CSS Grid, Flexbox)
- Metodología BEM para nombrado de clases
- Normalize.css
- Google Fonts (PT Sans + Open Sans)
- Modernizr (detección WebP)
- Imágenes optimizadas en formato WebP con fallback a JPG
- Lazy loading en imágenes

## Características del proyecto

- Diseño **responsivo** adaptado a mobile y desktop
- **Header con imagen de fondo** tipo hero con texto centrado
- Layout con **CSS Grid** en secciones de dos columnas (blog + sidebar, cursos, nosotros)
- Formulario de contacto estilizado con imagen decorativa superpuesta
- **WebP detection** con Modernizr para servir el formato correcto según el navegador
- Preload y prefetch configurados en `index.html` para mejorar el rendimiento percibido
- Footer consistente en todas las páginas


## Lo que aprendí

Este proyecto fue mi práctica de maquetado multipágina con CSS puro. Trabajé con CSS Grid para estructuras de dos columnas, BEM para mantener el CSS organizado y escalable, variables CSS para manejar la paleta de colores y tipografías desde un solo lugar, y técnicas básicas de performance como WebP, lazy loading y preload de recursos críticos.
