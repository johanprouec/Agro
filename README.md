# AgroLink — Ecosistema Agrotech Premium 🚀

> **"Conectando el campo colombiano mediante tecnología de punta y comercio justo."**

AgroLink es una **Aplicación de Página Única (SPA)** robusta que integra marketplace ganadero, gestión de tierras y servicios especializados. El proyecto ha evolucionado hacia una plataforma funcional con persistencia de datos y una experiencia de usuario de nivel SaaS.

## 🌟 Capacidades Clave

### 🏠 Home & Experiencia Visual
- **Video Hero Cinematográfico**: Integración de `VideoVaca.mp4` como fondo dinámico con efecto de paralaje.
- **Sección de Servicios**: Diseño de 4 columnas para acceso rápido a Mercado, Tierras, Gestión y Veterinaria.
- **Aesthetic Premium**: Uso de tipografías modernas y fondos atmosféricos agrícolas.

### 🐄 Mercado Ganadero Dinámico
- **Listados Reactivos**: Los anuncios se renderizan dinámicamente desde una base de datos local (`localStorage`).
- **Filtros Avanzados**: Búsqueda por Raza/Tipo y estado de certificación.
- **Publicación Real**: Formulario funcional para añadir nuevos lotes al mercado.

### 🗺️ Geoportal de Tierras & 3D
- **Mapa Interactivo**: Basado en Leaflet con marcadores de precio por hectárea y herramientas de dibujo.
- **TerrainForge 3D**: Integración de una potente herramienta de visualización para transformar planos 2D en modelos topográficos 3D interactivos.
- **Capas Analíticas**: Simulación de capas de Clima y Calidad de Suelo.

### 📊 Módulo de Registro de Producción
- **Seguimiento Técnico**: Registro real de pesajes, eventos de sanidad y alimentación.
- **Dashboard de Gestión**: KPIs en tiempo real (Población Total, Ganancia de Peso) que se actualizan automáticamente al registrar nuevos datos.

### 🔐 Autenticación y Perfiles
- **Gestión de Usuarios**: Flujo completo de Login y Registro con persistencia de sesión en `localStorage`.
- **Perfiles Personalizados**: Panel para editar datos del productor y gestionar su actividad.

## 🛠️ Stack Tecnológico
- **Frontend Core**: HTML5, JavaScript Vanilla (ES6+).
- **Styling**: Tailwind CSS (Efectos Glassmorphism & Agro-Green Palette).
- **Visualización 3D**: Three.js (vía TerrainForge).
- **Mapas**: Leaflet.js + Geoman.io.
- **Persistencia**: LocalStorage API.
- **Despliegue**: [Sitio en Vivo (Vercel)](https://agrolink-landing.vercel.app).

## 📁 Arquitectura del Proyecto
```text
Agro/
├── index.html           # Núcleo SPA: Lógica de Negocio y UI principal.
├── terrainforge.html    # Herramienta de visualización 3D de terrenos.
├── VideoVaca.mp4        # Video hero cinematográfico.
├── memory.md            # ADN del proyecto (Memoria para IA).
├── README.md            # Documentación de capacidades e hitos.
└── PROYECTO_AGROLINK.md  # Visión de negocio y roadmap.
```

## 📈 Hitos Recientes
1.  **Migración SPA**: Consolidación total de la plataforma en una sola página reactiva.
2.  **Dashboard Pro**: Implementación de KPIs dinámicos y registro de producción técnica.
3.  **Visualización Avanzada**: Integración de TerrainForge para análisis de tierras en 3D.
4.  **Optimización UI**: Rediseño del Home con video hero y grids de servicios balanceados.

---
© 2026 AgroLink — Potenciando el desarrollo rural con tecnología.
