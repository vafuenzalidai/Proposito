# Semana con Propósito — V1

Aplicación web móvil-first para planificación semanal y seguimiento personal.

## Qué incluye
- Agenda semanal con días laborales, trayectos, almuerzo bloqueado, fines de semana y feriados.
- Feriados chilenos 2026 precargados y consulta automática para otros años cuando hay conexión.
- Clases MBA quincenales, ancladas al viernes 23-10-2026 y sábado siguiente; el ancla es editable.
- Actividades manuales: reuniones, doctor, matrimonios, deporte, ocio y otros compromisos.
- Reubicación automática de un bloque diario de trabajo profundo de 90 min después de cargar reuniones.
- Check-in diario de KPIs y scorecards semanales/mensuales.
- Respaldo e importación de datos en JSON.
- PWA instalable si se publica por HTTPS.

## Uso recomendado
1. El domingo por la noche abre la pestaña Semana.
2. Carga reuniones y compromisos ya conocidos.
3. Presiona “Auto-ubicar foco 90 min”.
4. Recorre los 7 días y marca cada uno como planificado.
5. Cada noche completa el check-in de KPIs.

## Importante sobre notificaciones
Los avisos funcionan mientras la web/PWA está activa. Las notificaciones móviles garantizadas con la app completamente cerrada requieren un backend de push en una siguiente versión.

## Datos
V1 guarda todo en `localStorage` del navegador. Usa “Exportar JSON” como respaldo periódico.
