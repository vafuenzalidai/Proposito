# Happiness Management — V3.1

Aplicación web móvil para planificación semanal, registro diario y seguimiento de KPIs.

## Novedades V3

- Nuevo KPI **Lectura**, con meta inicial de **90 min/semana**.
- Metas de KPIs editables desde **Ajustes > Configuración de KPIs**.
- Posibilidad de crear KPIs personalizados sin modificar código.
- Los KPIs personalizados se registran diariamente en minutos y se evalúan contra una meta semanal.
- Los KPIs nuevos aparecen automáticamente en el registro diario, reportes y evolución de 12 meses.
- Se mantiene el historial, agenda y registros existentes de V2 usando la misma clave de almacenamiento local.
- Cache PWA actualizado a V3 para facilitar la actualización desde GitHub Pages.

## Metas iniciales

- Redes sociales: < 30 min/día
- Deporte: 180 min/semana
- Gimnasio: 120 min/semana
- Lectura: 90 min/semana
- Pareja: 120 min/semana
- Reflexión: 150 min/semana
- Comida no saludable: máximo 1/semana
- Alcohol: máximo 1 día/semana
- Conversación significativa: al menos 1/mes

## Actualizar en GitHub Pages

Reemplaza en la raíz del repositorio `index.html`, `sw.js`, `manifest.webmanifest`, `README.md`, `icon-192.png` e `icon-512.png`, y confirma el commit en la rama publicada por GitHub Pages.

Antes de una actualización importante es recomendable usar **Exportar JSON** desde la aplicación.


## Logo

Se agregó el archivo `logo-happiness-management.png` y se reemplazaron `icon-192.png` e `icon-512.png` por el nuevo logo de la app.


## Ajuste V3.1

Se corrigió el tamaño del logo en el encabezado agregando estilos para que la imagen se ajuste al contenedor sin desbordarse.
