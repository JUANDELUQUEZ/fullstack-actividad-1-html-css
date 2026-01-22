# JDigital - Soluciones de Software a Medida 

**JDigital** es una landing page corporativa diseñada para una empresa de desarrollo de software. Este proyecto demuestra la implementación de prácticas modernas de desarrollo web, enfocándose en la semántica HTML5, diseño responsivo (CSS Grid/Flexbox) y accesibilidad web.

**Ver Proyecto en Vivo:** [https://juandeluquez.github.io/fullstack-actividad-1-html-css/]

## Tabla de Contenidos
- [Descripción](#descripción)
- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instalación y Uso](#instalación-y-uso)
- [Autor](#autor)

## Descripción
El objetivo principal de este proyecto fue construir una interfaz web robusta y adaptable desde cero, sin depender de frameworks externos. La página incluye secciones informativas (Misión/Visión), una galería de servicios interactiva y un formulario de contacto funcional y accesible.

## Características Clave

### 1. Diseño Responsivo (Mobile-First)
- Adaptabilidad total a dispositivos móviles, tablets y escritorio.
- Uso de **Media Queries** para ajustar tipografías y layouts.
- Menú y galería de servicios que se transforman de una columna (móvil) a rejilla de tres columnas (escritorio).

### 2. Estilización Avanzada con CSS3
- Implementación de **CSS Grid** (`auto-fit`, `minmax`) para la galería de servicios.
- Uso de **Variables CSS (Custom Properties)** para una gestión eficiente de la paleta de colores (Modo Oscuro).
- Reset CSS y normalización de estilos base.
- Efectos de `hover` y transiciones suaves en tarjetas y botones.

### 3. Accesibilidad y Semántica  
- Uso correcto de etiquetas semánticas (`<header>`, `<main>`, `<article>`, `<footer>`).
- Textos alternativos (`alt`) descriptivos en todas las imágenes.
- Vinculación correcta de `<label>` con `<input>` en formularios para lectores de pantalla.
- Contraste de colores optimizado para legibilidad.

## Tecnologías Utilizadas
- **HTML5:** Estructura semántica.
- **CSS3:** Estilos, Grid Layout, Flexbox y Animaciones.
- **Git & GitHub:** Control de versiones y flujo de trabajo (GitFlow).
- **VS Code:** Editor de código.

## Estructura del Proyecto
```text
/
├── index.html          # Archivo principal con estructura semántica
├── styles/
│   └── styles.css      # Hoja de estilos con variables y media queries
├── img/                # Recursos gráficos optimizados
└── README.md           # Documentación del proyecto
