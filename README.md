# Portafolio Personal - Estudiante de Desarrollo de Software

Proyecto web desarrollado con **HTML5 Semántico**, **Tailwind CSS** y enfocado en el cumplimiento de pautas de accesibilidad **WCAG 2.1**.

## Estructura del Proyecto

```text
Portafolio/
├── assets/
│   └── img/                 # Carpeta para fotos e ilustraciones
├── index.html               # Archivo principal con HTML5 semántico
├── .gitignore               # Archivos ignorados por git
└── README.md                # Documentación del proyecto
```

## Criterios de Accesibilidad (WCAG) Aplicados

1. **Idioma de la página (`lang="es"`):** Facilita la síntesis de voz en lectores de pantalla (Criterio 3.1.1).
2. **Salto de navegación (`Skip Link`):** Permite a usuarios de teclado saltar al contenido principal directamente (Criterio 2.4.1).
3. **Jerarquía semántica clara:** Uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<footer>` y encabezados ordenados (`<h1>`, `<h2>`, `<h3>`) sin redundancia de `<div>` ni `<span>` innecesarios (Criterio 1.3.1).
4. **Contraste de color (Nivel AA):** Textos con contraste superior a 4.5:1 para garantizar lectura cómoda (Criterio 1.4.3).
5. **Foco visible:** Indicadores visuales en enlaces y botones interactivos para navegación por teclado (Criterio 2.4.7).
6. **Textos alternativos en imágenes:** Atributos `alt` contextuales en cada elemento visual (Criterio 1.1.1).
7. **Enlaces descriptivos:** Enlaces a GitHub con contexto claro para tecnología asistiva (Criterio 2.4.4).

