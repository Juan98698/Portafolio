# Portafolio Personal - Juan Manuel

Portafolio web desarrollado con **HTML5 Semántico**, **Tailwind CSS** y enfocado en el cumplimiento estricto de las pautas de accesibilidad **WCAG 2.1 (Nivel AA)**.

---

## Estructura del Proyecto

```text
Portafolio/
├── assets/
│   └── img/
│       ├── fotoJuan.png          # Fotografía de perfil
│       ├── hobby-gym.svg         # Ilustración: Entrenamiento pesado
│       ├── hobby-coding.svg      # Ilustración: Desarrollo & Tech
│       ├── hobby-miradores.svg   # Ilustración: Vistas nocturnas
│       └── hobby-cerveza.svg     # Ilustración: Cerveza helada & desconexión
├── index.html                    # Archivo principal semántico
├── .gitignore                    # Archivos ignorados por Git
└── README.md                     # Documentación y sustento técnico
```

---

## Secciones del Portafolio

1. **Cabecera y Navegación (`<header>`, `<nav>`):** 
   - Barra fija accesible con contraste adecuado y estados de foco visibles.
   - Enlaces de ancla a cada sección (`#sobre-mi`, `#proyectos`, `#hobbies`).
2. **Acerca de mí (`<section id="sobre-mi">`):**
   - Fotografía de perfil en `<figure>`, título principal `<h1>`, rol y lista semántica `<ul>` de tecnologías.
3. **Mis Proyectos (`<section id="proyectos">`):**
   - Tarjetas semánticas `<article>` para **Evolution Lab** y **Rueda Libre**.
   - Enlaces diferenciados y accesibles para **Demo en vivo / Sitio web** y **Código en GitHub**.
4. **Mis Hobbies (`<section id="hobbies">`):**
   - Tarjetas gráficas usando `<figure>` e imágenes SVG puras sin texto incrustado, con títulos y descripciones en `<figcaption>`.
5. **Pie de página (`<footer>`):**
   - Navegación secundaria con enlaces de autoría, GitHub y retorno al inicio.

---

## Criterios de Accesibilidad (WCAG 2.1) Aplicados

| Criterio | Nivel | Implementación en el Código |
| :--- | :--- | :--- |
| **3.1.1 Idioma de la página** | A | `<html lang="es">` para correcta pronunciación en lectores de pantalla. |
| **2.4.1 Omitir bloques** | A | Enlace de salto (*Skip Link*) visible con la tecla `Tab` para ir directo al contenido. |
| **1.3.1 Información y relaciones** | A | Estructura semántica sin *"divitis"*: jerarquía lógica (`h1` → `h2` → `h3`) y uso de `nav`, `main`, `section`, `article`, `figure`. |
| **1.1.1 Contenido no textual** | A | Atributos `alt` contextuales en fotos y gráficos; `aria-hidden="true"` en SVGs decorativos. |
| **1.4.3 Contraste mínimo** | AA | Ratios de contraste superiores a 4.5:1 en todos los textos sobre fondos claros y oscuros. |
| **1.4.5 Imágenes de texto** | AA | Las ilustraciones no contienen texto incrustado; los títulos residen en `<figcaption>` y encabezados. |
| **2.4.4 Propósito del enlace** | A | Atributos `aria-label` descriptivos que indican el proyecto y advierten si abren en nueva pestaña. |
| **2.4.7 Foco visible** | AA | Estados de foco evidentes (`focus:ring-2 focus:ring-offset-2`) en cada enlace interactivo. |
