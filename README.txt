CAR2026 - Prototipo iPhone 0.5

Contenido:
- index.html: aplicación web progresiva con identificación, provincias, búsqueda y selección múltiple de estaciones.
- stations.json: catálogo de 67 estaciones identificadas en el directorio oficial de estaciones fijas.
- manifest.webmanifest y sw.js: instalación y caché básica.
- iconos: icon-180.png, icon-192.png, icon-512.png.

Publicación GitHub Pages:
Subir el contenido de esta carpeta a la raíz del repositorio car2026-app/CAR2026 (no subir la carpeta contenedora).

Criterio del catálogo:
Se incluyen únicamente instalaciones identificadas como estaciones ITV fijas. Se excluyen laboratorios, unidades móviles, unidades móviles agrícolas y otros servicios no fijos. El catálogo se ha reconstruido a partir de las fichas visibles del directorio oficial VEIASA. La exhaustividad debe validarse contra la paginación completa del directorio oficial antes de usarlo como fuente definitiva.

Fuente: https://www.veiasa.es/web/guest/itv/estaciones-itv/estaciones-fijas
Fecha de consulta: 25/11/2026

Estado funcional:
La identificación, navegación, filtro de estaciones y selección múltiple funcionan en el navegador. No se envían datos del vehículo a un servidor. No existe conexión con la agenda de ITVCITA, no hay disponibilidad real ni monitorización en segundo plano. El botón de monitorización permanece deshabilitado.

Reserva:
La aplicación no realiza reservas ni resuelve CAPTCHA. La reserva se completa manualmente en https://www.itvcita.com/.
