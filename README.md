# Documentación de ForjaAnalytics

Centro de documentación técnica de los proyectos de ForjaAnalytics, publicado como
sitio estático en GitHub Pages.

**Sitio publicado:** https://forjaanalytics.github.io/Documentacion_forja_analytics/

## Estructura

```
index.html                  Catálogo principal "Documentación de ForjaAnalytics"
assets/catalog.css          Estilos del catálogo
emerald/                    Libro de documentación del proyecto Emerald
├── index.html              Portada / tabla de contenido (13 secciones)
├── 01-resumen.html ...     Una página por sección
├── 13-operacion.html
└── assets/docs.css         Hoja de estilos compartida por el libro
```

El catálogo (`index.html`) lista los proyectos documentados. Cada proyecto abre su
propio libro con índice y navegación entre páginas (anterior / índice / siguiente).

## Proyectos

| Proyecto | Estado | Documentación |
|----------|--------|---------------|
| Emerald  | Activo | `emerald/index.html` — 13 secciones (arquitectura, componentes, datos, API, infraestructura) |

## GitHub Pages

El sitio se sirve desde la rama `main`, carpeta raíz (`/`). Para activarlo:
**Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch:
`main` / `/ (root)` → Save.** El primer despliegue tarda ~1 minuto.

Es un sitio estático sin dependencias ni build step; cualquier `.html` puede abrirse
directamente en el navegador.
