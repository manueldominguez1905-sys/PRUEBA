# Constitución del Proyecto Control TUSSAM

## Artículo 1. Objetivo

El proyecto Control TUSSAM tiene como finalidad proporcionar una herramienta profesional, estable, escalable y fácil de mantener para la gestión integral del trabajo diario del conductor.

## Artículo 2. Principios

- La estabilidad siempre tendrá prioridad sobre las nuevas funciones.
- Toda nueva funcionalidad deberá ser compatible con las existentes.
- Se evitará duplicar código.
- Se priorizará la reutilización de componentes.
- La arquitectura prevalecerá sobre las soluciones rápidas.
- El diseño visual deberá mantenerse coherente en toda la aplicación.

## Artículo 3. Datos

Se distinguirán siempre dos tipos de datos:

- Datos Oficiales (calendarios laborales, convenios, tablas salariales, parámetros oficiales, etc.).
- Datos del Usuario (recaudaciones, liquidaciones, hojas de ruta, notas, incidencias, etc.).

Nunca deberán mezclarse.

## Artículo 4. Desarrollo

Toda modificación importante deberá:

1. Analizar el impacto.
2. Mantener la compatibilidad.
3. Documentarse.
4. Auditarse antes de incorporarse a la versión estable.

## Artículo 5. Filosofía

La aplicación crecerá mediante módulos independientes y reutilizables, manteniendo siempre una arquitectura clara y preparada para futuras ampliaciones.
