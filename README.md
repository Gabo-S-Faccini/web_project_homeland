# De patria a patria — TripleTen Art Gallery

## Descripción del proyecto

"De patria a patria" es un proyecto de galería de arte en línea creado para TripleTen, que presenta historias y fotografías de personas que colaboran con la comunidad tecnológica, compartiendo el lugar del que proceden. El proyecto consiste en la maquetación de una página web estática a partir de un diseño de Figma, replicando fielmente la tipografía, el espaciado, las imágenes y el comportamiento responsive definidos en el diseño original.

La página incluye un encabezado con el logo del proyecto, una sección principal con el título, un texto descriptivo y una imagen de portada, una sección de contenido con una cita destacada y texto explicativo, y un pie de página con información de autoría.

## Tecnologías y técnicas utilizadas

- **HTML5** semántico
- **CSS3**, organizado bajo la metodología **BEM** (Block, Element, Modifier), separando los estilos por bloque en archivos independientes (`header.css`, `main.css`, `content.css`, `footer.css`, etc.) e importados desde un archivo central (`index.css`)
- **Normalize.css** para unificar los estilos base entre navegadores
- **Tipografía autoalojada (self-hosted)**: familia Inter en múltiples pesos (100–900), cargada mediante `@font-face` en lugar de depender de un servicio externo
- **Diseño responsive** mediante:
  - Media queries para ajustar tipografía, márgenes y espaciados según el ancho de pantalla (breakpoints de escritorio, tablet y móvil)
  - La función `clamp()` para dimensionar elementos de forma fluida sin necesidad de múltiples breakpoints
  - `aspect-ratio` para mantener la proporción original de las imágenes en cualquier tamaño de pantalla
- Flexbox para la alineación y estructura de los bloques principales

## GitHub Pages

Puedes ver el proyecto en vivo aquí:
https://gabo-s-faccini.github.io/web_project_homeland/
