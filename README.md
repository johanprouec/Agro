# AgroLink — Ecosistema Agrotech Premium 🚀

> **"Conectando el campo colombiano mediante tecnología de punta y comercio justo."**

AgroLink es una **Aplicación de Página Única (SPA)** robusta que integra marketplace ganadero, gestión de tierras y servicios especializados. El proyecto ha evolucionado hacia una plataforma funcional con persistencia de datos y una experiencia de usuario de nivel SaaS.

## 🌟 Capacidades Clave

### 🏠 Home & Identidad
- **Sección Corporativa**: Misión y Visión integradas al inicio para una introducción profesional inmediata.
- **Micro-interacciones**: Hover effects y animaciones de entrada en cada componente.

### 🐄 Mercado Ganadero Dinámico
- **Listados Reactivos**: Los anuncios se renderizan dinámicamente desde una base de datos local (`localStorage`).
- **Filtros Avanzados**: Búsqueda por Raza/Tipo y estado de certificación.
- **Información Técnica**: Tarjetas detalladas con Peso, Edad y Cantidad de animales.
- **Publicación Real**: Formulario funcional para añadir nuevos lotes al mercado.

### 🗺️ Geoportal de Tierras
- **Mapa Interactivo**: Basado en Leaflet con marcadores de precio por hectárea.
- **Dibujo Geospacial**: Integración con Geoman para que los usuarios puedan delimitar sus terrenos.
- **Capas Analíticas**: Simulación de capas de Clima y Calidad de Suelo.

### 🔐 Autenticación y Perfiles
- **Gestión de Usuarios**: Flujo completo de Login y Registro.
- **Panel de Perfil**: Edición de datos personales y avatar con persistencia de sesión.

### 📊 Gestión Estratégica
- **Dashboard de KPIs**: Control de población, ventas mensuales y salud del hato.
- **Visualización de Datos**: Gráficos de proyección y sistema de alertas críticas.

## 🛠️ Stack Tecnológico
- **Frontend Core**: HTML5, JavaScript Vanilla (ES6+).
- **Styling**: Tailwind CSS (Efectos Glassmorphism & Agro-Green Palette).
- **Mapas**: Leaflet.js + Geoman.io.
- **Persistencia**: LocalStorage API.
- **Despliegue**: [Sitio en Vivo (Vercel)](https://agrolink-landing.vercel.app).

## 📁 Arquitectura del Proyecto
```text
Agro/
├── index.html           # El núcleo: SPA, Lógica de Negocio y Estilos.
├── memory.md            # ADN del proyecto (Memoria para IA).
├── README.md            # Guía principal de desarrollo.
└── PROYECTO_AGROLINK.md  # Visión de negocio y roadmap.
```

## 🚀 Instalación y Desarrollo
1. Clona el repositorio.
2. Abre `index.html` en cualquier navegador moderno.
3. Para ver los cambios en tiempo real, se recomienda usar un live server.

---
© 2026 AgroLink — Potenciando el desarrollo rural con tecnología.
