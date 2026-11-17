# Portafolio personal – Laura Sofía Agudelo Morales

Página de portafolio dirigida a reclutadores: presentación, sobre mí, habilidades, lo que estoy aprendiendo, proyecto destacado (**Rueda Libre**) y contacto. Desarrollada durante mi formación como coder en **Riwi**.

- 🔗 **Sitio publicado:** https://puella-non.github.io/pagina-personal/
- 📦 **Repositorio:** https://github.com/Puella-non/pagina-personal.git

## Tecnologías

- HTML5 semántico (`header`, `main`, `section`, `article`, `footer`)
- **Tailwind CSS v4** (CDN de jsDelivr) para el diseño y los estilos
- CSS propio mínimo (`CSS/styles.css`): variables de la paleta de colores, tipografía Poppins y color de los títulos
- Git y GitHub Pages

## Uso de Tailwind CSS

- Espaciados, tipografía, colores, bordes y sombras con clases de utilidad (`p-4`, `rounded-xl`, `shadow-lg`, `font-semibold`…).
- Colores de mi paleta conectados con Tailwind mediante valores arbitrarios: `from-[var(--titulos)]`, `bg-[var(--titulos)]`.
- Degradado en la cabecera con las utilidades de gradiente.
- Componentes armados con utilidades: etiquetas de habilidades, tarjeta del proyecto y botones.
- Estados `hover:` y `transition` en tarjeta y botones.
- Sin estilos en línea (`style=""`).

## Diseño responsive

Diseño *mobile first*: la base es para celular y los prefijos ajustan pantallas mayores.

| Prefijo | Qué cambia |
|---|---|
| Base (móvil) | Una columna, botones apilados, foto de perfil de 128 px |
| `sm:` (≥ 640 px) | Botones en fila, títulos y espaciados más grandes |
| `md:` (≥ 768 px) | Habilidades y Aprendiendo en 2 columnas, foto de 160 px, más espacio en la cabecera |
| `lg:` (≥ 1024 px) | Contenedor principal más ancho, foto y título más grandes |

## Estructura del proyecto

```
├── index.html
├── CSS/
│   └── styles.css
├── img/
│   └── foto-perfil.png
└── README.md
```

## Cómo ejecutarlo

Abre `index.html` en el navegador. Requiere conexión a internet para cargar Tailwind (CDN) y la fuente Poppins.

## Relación con Rueda Libre

Este es un proyecto independiente donde apliqué **Tailwind CSS**. **Rueda Libre**, donde trabajé con **Bootstrap**, está en su propio repositorio: <https://github.com/Puella-non/rueda-libre>

## Apoyo de IA

Para este proyecto usé Claude (IA de Anthropic) como apoyo para estructurar la página, aprender las clases de Tailwind y redactar este README. El contenido (mi perfil, mis habilidades, mi proyecto Rueda Libre y mis datos de contacto) es mío.