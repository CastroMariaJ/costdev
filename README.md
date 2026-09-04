# 🚀 Costodev S&M - Plataforma Web de Desarrollo de Software

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![FontAwesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)
![Status](https://img.shields.io/badge/Estado-Completado-brightgreen?style=for-the-badge)

**Costodev S&M** (Codedev S&M) es un sitio web empresarial multipágina diseñado y maquetado con HTML5 y CSS3 modular. El proyecto presenta una interfaz moderna, limpia y totalmente responsiva enfocada en la presentación de servicios de desarrollo de software, diseño digital, planes de precios y formulario de solicitud de demos.

---

## 📑 Tabla de Contenidos
- [Vista General](#-vista-general)
- [✨ Características Principales](#-características-principales)
- [🛠️ Tecnologías Utilizadas](#️-tecnologías-utilizadas)
- [📂 Estructura del Proyecto](#-estructura-del-proyecto)
- [🚀 Instalación y Uso](#-instalación-y-uso)


---

## 📋 Vista General

El portal **Costodev S&M** ofrece una experiencia de usuario fluida a través de múltiples secciones navegables:
- **Página de Inicio (`index.html`)**: Presentación general de la marca, propuesta de valor y servicios destacados.
- **Diseño (`design.html`)**: Catálogo de soluciones de diseño UI/UX y creación visual.
- **Plataforma (`platform.html`)**: Explicación detallada de la arquitectura técnica e infraestructura de soluciones.
- **Precios (`pricing.html`)**: Comparativa de planes comerciales y suscripciones.
- **Solicitud / Cotización (`request.html`)**: Formulario de contacto directo y solicitud de servicios.
- **Facturación (`factura.html`)**: Vista de plantilla de factura/resumen de servicios.

---

## ✨ Características Principales

- 📱 **Diseño Adaptativo (Responsive Design)**: Ajuste perfecto para dispositivos móviles, tablets y monitores de escritorio mediante media queries dedicadas.
- 🎨 **Estilos Modulares en CSS**: Organización limpia del código CSS dividida por componentes (`header`, `footer`, `home-main`, `design-main`, `plataforma-main`).
- 🍔 **Menú Hamburguesa Interactivo**: Navegación móvil construida en CSS puro utilizando la técnica del *checkbox hack* sin necesidad de JavaScript pesado.
- 🔤 **Iconografía con FontAwesome 6.5**: Iconos vectoriales de alta definición para navegación y elementos de interfaz.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica para la web.
- **CSS3**: Maquetación avanzada, Flexbox, CSS Grid y Media Queries.
- **FontAwesome 6.5.1**: Biblioteca de iconos web.
- **Google Fonts**: Tipografías modernas.

---

## 📂 Estructura del Proyecto

```file-tree
ProyectoCSS/
├── index.html                  # Página principal de Inicio
├── design.html                 # Sección de servicios de diseño UI/UX
├── platform.html               # Información sobre la plataforma técnica
├── pricing.html                # Tabla de planes y precios
├── request.html                # Formulario de solicitud y contacto
├── factura.html                # Plantilla de facturación/resumen
├── estilos/                    # Hojas de estilo CSS modulares
│   ├── estilo.css              # Estilos generales y variables
│   ├── header.css              # Estilos de la barra de navegación superior
│   ├── footer.css              # Estilos del pie de página
│   ├── home-main.css           # Estilos de la landing principal
│   ├── design-main.css         # Estilos de la página de diseño
│   ├── plataforma-main.css     # Estilos de la vista de plataforma
│   └── reponsive-media/        # Hojas de estilo específicas para pantallas móviles
│       ├── index-responsive.css
│       ├── design-responsive.css
│       └── plataforma-responsive.css
└── img/                        # Recursos visuales e imágenes del proyecto
    └── logo_page-removebg.png
```

---

## 🚀 Instalación y Uso

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/CastroMariaJ/costdev.git
   ```

2. **Abrir el proyecto**:
   - Navega a la carpeta del proyecto.
   - Abre el archivo `index.html` en tu navegador web preferido (Google Chrome, Firefox, Edge, etc.) o utiliza la extensión **Live Server** en VS Code.


