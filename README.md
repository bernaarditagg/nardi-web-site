# Nardi — Sitio web

Portafolio web de Nardi, un estudio de marketing digital. Proyecto desarrollado como práctica final del curso de Desarrollo Web de Coderhouse.

## Sitio desplegado

🔗 https://bernaarditagg.github.io/nardi-web-site/

## Tecnologías utilizadas

- HTML5 semántico
- CSS3 (variables, Flexbox, CSS Grid, Media Queries)
- [Bootstrap 5](https://getbootstrap.com/) (Navbar responsiva y Carousel), personalizado con estilos propios sobre la paleta de colores del proyecto
- Git y GitHub para el control de versiones

## Estructura del proyecto

```
nardi-web-site/
├── index.html
├── pages/
│   ├── quienes-somos.html
│   ├── nuestros-trabajos.html
│   ├── proceso.html
│   └── contacto.html
├── styles/
│   └── styles.css
└── img/
    └── nardi-logo.png
```

## Páginas

- **Inicio** (`index.html`): presentación de la marca, servicios y galería de proyectos con Carousel.
- **Quiénes somos** (`pages/quienes-somos.html`): historia y enfoque del estudio.
- **Nuestros trabajos** (`pages/nuestros-trabajos.html`): casos de éxito con tarjetas y galería de piezas.
- **Proceso** (`pages/proceso.html`): metodología de trabajo en 5 pasos.
- **Contacto** (`pages/contacto.html`): datos de contacto y horarios de atención.

## Diseño responsivo

El sitio sigue una estrategia **mobile-first**: la base está pensada para pantallas chicas y, a partir de los 1024px de ancho, algunas secciones pasan a usar CSS Grid para aprovechar mejor el espacio en pantallas grandes (portada, galería de trabajos y pasos del proceso).
