Proyecto SmartBudget - Landing Page
Este repositorio contiene el código fuente para la Landing Page de SmartBudget, una aplicación web enfocada en la gestión inteligente de finanzas personales. Este proyecto ha sido desarrollado siguiendo las mejores prácticas y requerimientos técnicos del Módulo 3 de Desarrollo Web de Alkemy.

🚀 Tecnologías y Metodologías Utilizadas
El proyecto se destaca por su estructura modular y profesional, utilizando las siguientes tecnologías:

HTML5: Estructura semántica y accesible.

SASS (CSS Preprocessor): Utilizado para escribir estilos mantenibles y escalables.

Arquitectura 7-1: Organización de los estilos SASS en siete carpetas distintas (abstracts, base, components, layout, pages, themes, vendors) para una modularización óptima.

Metodología BEM (Block, Element, Modifier): Convención de nomenclatura para clases CSS, garantizando un código limpio y sin colisiones de estilos.

Bootstrap 4: Framework CSS utilizado para acelerar el desarrollo del layout y garantizar la responsividad del sitio.

Responsive Design: Enfoque "Mobile-First" para asegurar una correcta visualización en dispositivos móviles, tablets y escritorios.

📂 Estructura del Directorio
La organización de los archivos sigue el patrón 7-1 de SASS:

Plaintext
PROYECTO-SMARTBUDGET/
│
├── index.html              // Archivo principal de la Landing Page
├── justificacion.md        // Documento breve con la justificación metodológica
│
├── /css                    // Carpeta contenedora del CSS compilado
│   └── main.css            // Archivo CSS generado automáticamente por SASS
│
└── /sass                   // Carpeta raíz de los archivos SASS
    ├── main.scss           // Archivo principal que importa todos los parciales
    │
    ├── /abstracts          // Variables, mixins y funciones
    │   └── _variables.scss
    │
    ├── /base               // Estilos base (reset, tipografía)
    │   └── _reset.scss
    │
    ├── /components         // Componentes reutilizables (cards, botones)
    │   └── _cards.scss
    │
    ├── /layout             // Estilos de la estructura (header, footer, grid)
    │   └── _header.scss
    │
    └── ...                 // (Otras carpetas de la arquitectura 7-1)
✨ Características Principales
Header Semántico: Incluye una barra de navegación (Navbar) de Bootstrap totalmente responsiva.

Sección Hero: Presentación impactante del producto con un llamado a la acción (CTA) claro.

Sección Features (Características): Uso de componentes Cards de Bootstrap para mostrar las funcionalidades clave de SmartBudget de forma ordenada y visualmente atractiva.

Footer: Sección final con información de derechos de autor y enlaces de contacto.

Desarrollado con fines académicos para Alkemy.
