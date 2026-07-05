# Justificación Metodológica - Proyecto SmartBudget

## Arquitectura y Organización (7-1)
Se ha implementado una estructura de carpetas 7-1 para SASS, organizando el código en:
- `abstracts/`: Variables y mixins (colores, fuentes).
- `base/`: Estilos base y reset universal.
- `layout/`: Estructura principal (header, footer).
- `components/`: Elementos reutilizables (cards, botones).

Esta modularización mejora la mantenibilidad y escalabilidad del proyecto.

## Metodología CSS (BEM)
Se ha utilizado la nomenclatura **BEM** (`Bloque__Elemento--Modificador`) para nombrar las clases CSS. Esto evita colisiones de estilos y hace que el código sea más predecible y legible.
Ejemplo: `.card__title` (elemento), `.card--destacada` (modificador).

## Layout y Responsividad
El layout se ha construido siguiendo un enfoque **Mobile-First** y utilizando el sistema de grilla, flexbox y utilidades de **Bootstrap 4**. Esto garantiza una correcta visualización en dispositivos móviles y de escritorio sin necesidad de escribir media queries complejas desde cero.

## Semántica Web
Se han utilizado etiquetas semánticas de HTML5 (`<header>`, `<main>`, `<section>`, `<footer>`) para mejorar la accesibilidad y el SEO del sitio.