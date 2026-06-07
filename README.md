# 🐘 SEMANA 15: Gestión de Alojamientos Turísticos
### *Análisis, CRUD y JOINs en PostgreSQL*

Este repositorio contiene el script estructurado `ConsultasSemana15-JC.sql` con las 20 consultas guiadas requeridas para la gestión de alquileres vacacionales[cite: 1, 2].

---

## ⚙️ Motor Utilizado: PostgreSQL 🐘

La solución fue desarrollada y ejecutada sobre el motor relacional **PostgreSQL**, utilizando **pgAdmin 4** como entorno de desarrollo principal.

### ¿Por qué PostgreSQL?
* **Tipado Estricto:** Manejo nativo e impecable de estados booleanos (`true`/`false`) y datos temporales (`DATE`)
* **Eficiencia en JOINS:** Excelente optimización del *Query Planner* para resolver consultas multilaterales complejas
* **Cumplimiento ACID:** Garantía total de integridad en operaciones críticas como la gestión de `pagos` y `reservas`

---

## 🗺️ Estructura del Script

El archivo se divide en dos grandes bloques tácticos

1. **Operaciones CRUD (01 - 10):** Inserciones atómicas de datos, control de rangos de fechas con `BETWEEN`, actualización de tarifas y eliminación controlada con verificación inmediata.
2. **Consultas Avanzadas (11 - 20):** Combinación de tablas (`INNER` y `LEFT JOIN`), auditoría de registros huérfanos (`IS NULL`), métricas financieras (`SUM`, `AVG`), límites y subconsultas complejas


