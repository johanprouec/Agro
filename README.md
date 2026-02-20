# AgroLink — Marketplace Agrotech

> **"Conectamos el campo con el mercado digital."**

AgroLink es una plataforma digital agrotech diseñada para transformar el sector agropecuario. Conecta de manera directa a productores, compradores, propietarios de tierras y proveedores de servicios, reduciendo la informalidad y los intermediarios mediante tecnología accesible y confiable.

## 🚀 Características Principales

-   **Marketplace de Ganado:** Publicación y comercialización de ganado con detalles técnicos, fotos y geolocalización.
-   **Arriendo de Terrenos:** Oferta y demanda de fincas y lotes para engorde o cultivo con información clara sobre recursos (agua, accesos).
-   **Servicios Veterinarios:** Directorio de profesionales verificados con sistema de calificaciones por zona.
-   **Módulo de Registro Productivo:** Herramienta para que agricultores y ganaderos gestionen datos de producción, cosechas y rendimientos.
-   **Búsqueda Inteligente:** Filtros avanzados por ubicación, tipo de producto y rangos de precio.

## 🛠️ Tecnologías

-   **Frontend:** HTML5, Tailwind CSS (via CDN) y JavaScript (Vanilla).
-   **Despliegue:** [Vercel](https://vercel.com).
-   **Diseño:** Interfaz modular SPA, responsiva y orientada a la experiencia del productor.

## 📁 Estructura del Proyecto

```text
Agro/
├── index.html     # Aplicación Principal (SPA: Inicio, Ganado, Tierras, Vet, Gestión)
├── memory.md      # Contexto y objetivos de la Start-up
├── README.md      # Documentación del proyecto
└── PROYECTO_AGROLINK.md # Visión de negocio detallada
```

## 💻 Desarrollo Local

1. Clona el repositorio.
2. Abre `index.html` en tu navegador o usa una extensión como "Live Server".

## 🚀 Despliegue

La plataforma está configurada para desplegarse automáticamente en **Vercel**.

### Opción 1: Git (Recomendado)
Cualquier cambio empujado a la rama `main` activará un despliegue automático:
```bash
git add .
git commit -m "feat: descripción del cambio"
git push origin HEAD
```

### Opción 2: Vercel CLI
Para despliegues manuales inmediatos:
```bash
npx vercel --prod
```

## 📈 Visión

Ser la plataforma de referencia en Colombia para la comercialización y gestión productiva rural, eliminando asimetrías de información y empoderando al productor con datos reales.

---
© 2026 AgroLink — Hecho para el sector rural.
