# SIE Lab · Del mapa a la decisión

Web estática para un laboratorio de QGIS de 120 minutos: agroalimentación, salud comunitaria y movilidad. Incluye tutoriales guiados, comprobaciones, simuladores y datos descargables.

## Abrir

Se publica con GitHub Pages desde `main`, carpeta raíz. `.nojekyll` evita procesamiento adicional. No hay compilación ni dependencias externas. Para servir en local: `python -m http.server 8765` desde esta carpeta.

## Contenido

- `index.html`, `styles.css`, `app.js`, `tutorials.js`: sitio y tutoriales.
- `assets/`: mapas renderizados en QGIS con los datos del laboratorio.
- `downloads/`: datos por sector y completos, PDFs de alumnado/docente y material opcional del Modelador.

## Alcance de los datos

Todos los escenarios son simulados y sus coordenadas solo sirven a la actividad. No contienen datos de pacientes, producción real ni servicios operativos. Los resultados no deben trasladarse a decisiones reales. Los enlaces EEA, DERA y NAP orientan ampliaciones y no son la fuente de los datos sintéticos incluidos.

Las operaciones del material se probaron con QGIS 3.42.1. Las etiquetas de herramientas pueden variar por versión y traducción. El simulador del navegador es didáctico; no ejecuta QGIS.

## Privacidad y accesibilidad

Sin analítica, formularios, cuentas ni servicios de terceros. El progreso se guarda solo en `localStorage` del navegador. Botones y pestañas son accesibles con teclado; los PDFs y datos siguen disponibles si JavaScript está desactivado.

La guía docente está identificada como material con soluciones, desplegado aparte. No existe una barrera de acceso: el sitio es público para el alumnado.
