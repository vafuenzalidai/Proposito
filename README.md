# Semana con Propósito — V2

Aplicación web móvil-first para planificación semanal, seguimiento personal y KPIs.

## Cambios V2

- Nueva pestaña **Evolución** con gráficos mensuales de los últimos 12 meses para cada KPI.
- El registro diario puede completarse o editarse durante todo el día y también en fechas anteriores.
- Nuevo KPI **Gimnasio**, meta: **120 min/semana**.
- Meta de **Deporte** actualizada a **180 min/semana**.
- Reportes semanales y mensuales navegables hacia períodos anteriores.
- Los registros permanecen en `localStorage`; la evolución está diseñada para consultar al menos 12 meses.
- Service worker actualizado a V2 para evitar que GitHub Pages/PWA siga mostrando la versión anterior.

## Actualizar en GitHub Pages

1. En el repositorio, reemplazar `index.html`, `sw.js`, `manifest.webmanifest`, `README.md` y los íconos por los archivos de esta carpeta.
2. Hacer **Commit changes** sobre `main`.
3. GitHub Pages volverá a desplegar automáticamente.
4. En el celular, abrir la app con conexión a internet una vez. Si siguiera mostrando V1, cerrar la PWA completamente y volver a abrirla; como último recurso, quitarla de pantalla de inicio y agregarla nuevamente.

## Datos existentes

La V2 mantiene la misma clave de almacenamiento (`semana_proposito_v1`) para conservar los datos de la V1 en el mismo navegador/dispositivo. Los registros anteriores no tienen `gym`; se interpretan como 0 minutos hasta que sean editados.
