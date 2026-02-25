# AgroLink — Ecosistema Agrotech Premium

> **"La plataforma definitiva para la gestión y comercio del sector agropecuario."**

AgroLink ha evolucionado de una landing page a una **Aplicación de Página Única (SPA)** de alto rendimiento, diseñada con una estética SaaS premium. Conecta a productores, inversionistas y profesionales del campo mediante una interfaz intuitiva, inmersiva y funcional.

## 🌟 Estado Actual y Capacidades

### 1. Interfaz Inmersiva (UI/UX)
- **Navegación SPA**: Transiciones fluidas entre secciones (Inicio, Ganado, Tierras, Veterinarios, Gestión) sin recargar la página.
- **Diseño Glassmorphism**: Uso de transparencias, desenfoques de fondo y gradientes sofisticados (Agro-Green & Earth).
- **Fondos Dinámicos**: La atmósfera visual del sitio cambia automáticamente según la sección activa, mejorando la inmersión del usuario.

### 2. Mercado y Tierras (Contenido Coherente)
- **Ganado Certificado**: Listados detallados de bovinos (Angus, Brahman, Holstein, Charolais) y equinos (Paso Fino, Cuarto de Milla) con imágenes de alta fidelidad.
- **Geoportal de Tierras**: Layout de pantalla dividida (estilo Airbnb) con tarjetas interactivas de fincas en Tolima, Boyacá y el Cesar.
- **Directorio Médico**: Profesionales con perfiles verificados y estados de disponibilidad en tiempo real.

### 3. Interactividad Avanzada
- **Global Detail Modal**: Sistema centralizado para visualizar detalles técnicos de cualquier animal, propiedad o servicio.
- **Formularios de Acción**: Sistema de modales funcionales para:
    - **Publicar Venta** (Mercado).
    - **Agregar Terreno** (Tierras).
    - **Agendar Consulta** (Veterinarios).
- **Buscador Inteligente**: Barra de búsqueda integrada que filtra y redirige al mercado global.

## 🛠️ Stack Tecnológico

-   **Frontend**: HTML5, Tailwind CSS (Custom Config), JavaScript (ES6+ Vanilla).
-   **Componentes**: Lucide-inspired Material Symbols, Tipografía Inter & Crimson Pro.
-   **Despliegue**: [AgroLink Live](https://agrolink-landing.vercel.app).

## 📁 Estructura del Ecosistema

```text
Agro/
├── index.html     # El corazón: SPA, Lógica de Modales, Estilos y Estructura.
├── memory.md      # ADN del proyecto y contexto del asistente AI.
├── README.md      # Esta guía maestra de desarrollo.
└── PROYECTO_AGROLINK.md # Visión estratégica y roadmap de negocio.
```

## 🚀 Guía de Continuación

Para retomar el trabajo, simplemente revisa `index.html`. La arquitectura está centralizada en tres pilares:
1.  **Lógica de Navegación (`showSection`)**: Controla la visibilidad y los cambios de fondo dinámicos.
2.  **Sistema de Modales (`openDetails` / `openActionModal`)**: Gestiona toda la interacción de datos.
3.  **Configuración Tailwind**: Capa de diseño personalizada en el `<style>` del header.

---
© 2026 AgroLink — Tecnología para el campo colombiano.
