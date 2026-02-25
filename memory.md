# 🧠 AgroLink: El Cerebro del Proyecto

Este documento actúa como la memoria central y guía para "La K" (Asistente IA) y el desarrollador.

## 🚀 Identidad y Propósito
**AgroLink** es una plataforma agrotech diseñada para revolucionar el campo colombiano. Conecta a productores, compradores y arrendatarios en un ecosistema digital profesional y accesible.

## 🛠️ Estado Actual (Hitos Alcanzados)

### 1. Arquitectura SPA y Diseño Premium
- **Layout Expansivo**: Refactorizado a pantalla completa (`max-w-[1500px]`) para una visualización SaaS profesional.
- **Navegación Dinámica**: Sistema de secciones (`showSection`) con cambios de fondo y atmósfera visual según el contexto.
- **Estética**: Basada en Tailwind CSS con efectos de glassmorphism y micro-animaciones.

### 2. Autenticación y Perfiles
- **Sistema de Acceso**: Modal de Login/Registro funcional.
- **Persistencia**: Sesión de usuario guardada en `localStorage`.
- **Gestión de Perfil**: Modal para editar nombre, descripción, ubicación y foto de avatar.

### 3. Sistema de Listados Dinámicos (Motor de Datos)
- **Persistencia Local**: Todos los anuncios (ganado, tierras, veterinarios) se gestionan mediante un array global sincronizado con `localStorage`.
- **Publicación Real**: Formulario de "Publicar Venta" que añade nuevos elementos al sistema en tiempo real.
- **Detalle Global**: Modal centralizado para ver información técnica de cualquier ítem.

### 4. Mapas e Inteligencia Geoespacial
- **Integración Leaflet**: Mapa interactivo en la sección de tierras.
- **Herramientas de Dibujo**: Integración de `Geoman.io` para delimitar áreas directamente en el mapa.
- **Capas Analíticas**: Simulación de capas para Clima y Calidad de Suelo.

### 5. Secciones de Negocio
- **Mercado Ganadero**: Filtros por raza/tipo y tarjetas con peso, edad y cantidad.
- **Directorio Veterinario**: Perfiles profesionales con sistema de calificación y agenda.
- **Panel de Gestión**: Dashboard con KPIs, gráficos de proyección y alertas críticas.
- **Introducción Corporativa**: Sección "Quiénes Somos" con Misión y Visión al inicio del Home.

## 🔑 Instrucciones para la IA ("La K")
1.  **Consistencia**: Siempre mantén el diseño expansivo y los estilos premium (Agro-Green).
2.  **Integridad**: Antes de modificar el layout, verifica que los filtros y componentes dinámicos no se pierdan.
3.  **Persistencia**: Cualquier dato nuevo (usuario, anuncio) debe sincronizarse con `localStorage` hasta que exista un backend real.
4.  **Prioridad**: El usuario debe sentir que la app está "viva" y es profesional.

---
*Última actualización: 24 de Febrero, 2026*