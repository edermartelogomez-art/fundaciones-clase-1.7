FUNDACIONES · CLASE 1 — PWA

Contenido principal
- index.html: aplicación completa.
- styles.css: interfaz responsiva para proyección, computador y móvil.
- app.js: navegación, simuladores, gráficas SVG, ejemplos y retroalimentación.
- manifest.webmanifest y sw.js: instalación y funcionamiento sin conexión.
- assets/: imágenes e iconos locales.

Publicación
1. Sube todo el contenido de esta carpeta al mismo directorio de GitHub Pages.
2. La PWA debe abrirse mediante HTTPS; no funciona como instalable desde file://.
3. Después de actualizar una versión publicada, recarga una vez para que el nuevo service worker reemplace la caché anterior.

La aplicación no necesita librerías externas ni conexión a internet después de su primera carga.

CORRECCIÓN v8
- Se eliminó la franja artificial que hacía parecer cortada la imagen principal.
- Se ajustó la proporción del recurso visual al contenedor real de la app.
- Se cambió el nombre del archivo y la versión de caché para forzar su actualización en GitHub Pages/PWA.
