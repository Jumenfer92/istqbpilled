# ISTQB CTFL en 90 minutos

Guía de estudio Pareto para el ISTQB CTFL v4.0, instalable como app en el móvil (PWA) y usable sin conexión.

## Publicar

1. Crea un repositorio en GitHub y sube todos estos archivos tal cual (la carpeta `icons` incluida).
2. En vercel.com → **Add New → Project** → importa el repositorio → **Deploy**. No hay que configurar nada: es un sitio estático.
3. Abre la URL de Vercel en Chrome del Android. A los 10 segundos aparece la ventana “¿Guardar como aplicación?”.

## Archivos

- `index.html` – la guía
- `manifest.webmanifest` – nombre, icono y colores de la app
- `sw.js` – guarda la guía para usarla sin conexión
- `icons/` – iconos de la app
- `vercel.json` – cabeceras para que el service worker se actualice bien

Si editas `index.html`, cambia `VERSION` en `sw.js` (p. ej. `ctfl-v2`) para que el móvil descargue la versión nueva.
