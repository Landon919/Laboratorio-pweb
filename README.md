# Laboratorio-pweb

Sitio web para una cafetería, desarrollado con HTML y CSS.

## Objetivo

Crear una página web responsiva y accesible que presente una cafetería en tres secciones:

- **Inicio:** bienvenida y descripción del lugar.
- **Productos:** catálogo de bebidas y postres con sus precios.
- **Contacto:** dirección, horario y formulario para enviar un mensaje.

El proyecto busca practicar el uso de etiquetas semánticas de HTML5, el diseño con Flexbox y Grid, el diseño responsivo y las buenas prácticas de accesibilidad.

## Tecnologías

| Tecnología | Uso en el proyecto |
|---|---|
| **HTML5** | Estructura de la página con etiquetas semánticas: `header`, `nav`, `main`, `section`, `article`, `address` y `footer`. |
| **CSS3** | Estilos en una hoja externa (`cafe.css`) con variables CSS para la paleta de colores. |
| **Flexbox** | Barra de navegación y portada de la sección Inicio. |
| **CSS Grid** | Tarjetas de productos y bloque de contacto. |
| **Media queries** | Un breakpoint en 700px para adaptar el diseño a pantallas móviles. |
| **SVG** | Imagen de la taza de café (`taza.svg`). |

## Accesibilidad

- Texto alternativo en las imágenes.
- Etiquetas `label` asociadas a cada campo del formulario.
- Jerarquía de encabezados ordenada (`h1`, `h2`, `h3`).
- Navegación clara, con enlace para saltar al contenido y contorno de enfoque visible.
- Colores con contraste legible.

## Estructura del proyecto

```
├── index.html   # Página principal
├── cafe.css     # Hoja de estilos
├── taza.svg     # Imagen de la portada
└── README.md
```
