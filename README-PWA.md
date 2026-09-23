# Mantenia PWA

Esta versión convierte Mantenia en una PWA instalable y con funcionamiento offline.

Archivos:
- index.html: aplicación
- manifest.webmanifest: identidad de la PWA
- sw.js: caché y funcionamiento offline
- icons/: iconos de instalación

IMPORTANTE:
Una PWA necesita servirse por HTTPS para que el Service Worker funcione en producción.
Para una publicación gratuita puedes usar un hosting estático que proporcione HTTPS.

Android:
1. Abre la URL de Mantenia en Chrome.
2. Usa "Instalar aplicación" / "Añadir a pantalla de inicio".
3. Mantenia aparecerá como una app.

iPhone/iPad:
1. Abre la URL en Safari.
2. Pulsa Compartir.
3. Pulsa "Añadir a pantalla de inicio".
4. Abre Mantenia desde el icono.

Los datos de esta versión siguen siendo locales al navegador/dispositivo.
