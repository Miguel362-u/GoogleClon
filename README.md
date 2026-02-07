# 🔍 GoogleClon

Un clon de la interfaz de Google creado con HTML y CSS puro, replicando el diseño moderno y minimalista del buscador más popular del mundo con tema oscuro.

## 📋 Descripción

Este proyecto es una recreación no exactamente fiel de la página principal de Google, implementada como proyecto de práctica para mejorar habilidades en maquetación web, diseño responsivo y CSS Grid/Flexbox. Incluye un tema oscuro que proporciona una experiencia visual moderna y cómoda.

## ✨ Características

- 🎨 **Tema Oscuro**: Diseño completo con paleta de colores oscuros
- 🔍 **Barra de búsqueda funcional**: Campo de búsqueda con iconos interactivos
- 🖼️ **Búsqueda por imagen**: Funcionalidad para agregar archivos
- 🎤 **Búsqueda por voz**: Icono de micrófono integrado
- 🤖 **Modo IA**: Botón especial para búsqueda con inteligencia artificial
- 🌐 **Navegación completa**: Header con enlaces a Gmail e Imágenes
- 👤 **Perfil de usuario**: Icono de cuenta personalizado
- 📍 **Footer localizado**: Información regional (Colombia)

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica del documento
- **CSS3**: Estilos y diseño visual
  - CSS Grid
  - Flexbox
  - Media Queries
- **Google Fonts**: Tipografía Roboto
- **SVG**: Iconos vectoriales escalables

## 📁 Estructura del Proyecto

```md
GoogleClon/
│
├── docs/
│   ├── index.html          # Página principal
│   ├── styles.css          # Estilos globales
│   ├── img/                # Imágenes del proyecto
│   │   └── SilverSurferG-Icon.jpg
│   └── svg/                # Iconos SVG
│       ├── apps.svg
│       ├── google-plain-wordmark.svg
│       ├── microphone.svg
│       ├── plus.svg
│       ├── scan-search.svg
│       └── search.svg
│
└── README.md               # Este archivo
```

## 🚀 Instalación y Uso

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/tu-usuario/GoogleClon.git
   ```

2. **Navegar al directorio**

   ```bash
   cd GoogleClon/docs
   ```

3. **Abrir en el navegador**
   - Abrir el archivo `index.html` directamente en tu navegador
   - O usar Live Server en VS Code para desarrollo

## 🎯 Funcionalidades Implementadas

### Header

- Navegación superior con enlaces a Gmail e Imágenes
- Menú de aplicaciones de Google
- Icono de cuenta de usuario con imagen personalizada

### Sección Principal

- Logo de Google con efectos visuales
- Barra de búsqueda con múltiples opciones:
  - Búsqueda por texto
  - Cargar archivos/imágenes
  - Búsqueda por voz
  - Búsqueda visual
  - Modo IA
- Botones de acción:
  - "Buscar con Google"
  - "Voy a tener suerte"

### Footer

- Información de ubicación (Colombia)
- Enlaces a información corporativa
- Enlaces a privacidad y configuración
- Diseño responsivo con flex-wrap

## 💡 Conceptos Aprendidos

- Uso avanzado de CSS Grid para layout principal
- Implementación de Flexbox para componentes
- Diseño de interfaces oscuras con paletas de colores apropiadas
- Manejo de filtros CSS (invert, opacity)
- Diseño responsive con media queries
- Metodología BEM para nomenclatura de clases CSS
- Optimización de imágenes SVG

## 🎨 Paleta de Colores

- **Fondo principal**: `#1f1f1f`
- **Elementos secundarios**: `#303134`
- **Barra de búsqueda**: `#4d5156`
- **Texto**: `#ffffff`
- **Overlay footer**: `#00000050`

## 📱 Responsividad

El diseño se adapta a diferentes tamaños de pantalla:

- **Desktop**: Layout completo con todos los elementos
- **<1200px**: Footer con ajuste automático de elementos

## 🔮 Futuras Mejoras

- [ ] Implementar funcionalidad de búsqueda real
- [ ] Agregar más interactividad con JavaScript
- [ ] Integrar con API de Google Custom Search
- [ ] Añadir más breakpoints para móviles
- [ ] Implementar autocompletado en la barra de búsqueda
- [ ] Agregar animaciones y transiciones
- [ ] Modo claro/oscuro intercambiable

## 👨‍💻 Autor

**Miguel**
[email](rodriguezmiguel9193@gmail.com)

## 📄 Licencia

Este proyecto es de código abierto y está disponible para fines educativos.
