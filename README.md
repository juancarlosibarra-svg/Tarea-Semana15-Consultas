# 🐘 Proyecto: Gestión de Alojamientos Turísticos
### *Análisis, CRUD y JOINs en PostgreSQL*

Este repositorio contiene el script estructurado `ConsultasSemana15-JC.sql` con las 20 consultas guiadas requeridas para la gestión de alquileres vacacionales[cite: 1, 2].

---

## ⚙️ Motor Utilizado: PostgreSQL 🐘

La solución fue desarrollada y ejecutada sobre el motor relacional **PostgreSQL**, utilizando **pgAdmin 4** como entorno de desarrollo principal.

### ¿Por qué PostgreSQL? 🧠
* **Tipado Estricto:** Manejo nativo e impecable de estados booleanos (`true`/`false`) y datos temporales (`DATE`)[cite: 1, 2].
* **Eficiencia en JOINS:** Excelente optimización del *Query Planner* para resolver consultas multilaterales complejas[cite: 1, 2].
* **Cumplimiento ACID:** Garantía total de integridad en operaciones críticas como la gestión de `pagos` y `reservas`[cite: 1, 2].

---

## 🗺️ Estructura del Script

El archivo se divide en dos grandes bloques tácticos[cite: 2]:

1. **Operaciones CRUD (01 - 10):** Inserciones atómicas de datos, control de rangos de fechas con `BETWEEN`, actualización de tarifas y eliminación controlada con verificación inmediata[cite: 1, 2].
2. **Consultas Avanzadas (11 - 20):** Combinación de tablas (`INNER` y `LEFT JOIN`), auditoría de registros huérfanos (`IS NULL`), métricas financieras (`SUM`, `AVG`), límites y subconsultas complejas[cite: 1, 2].

---

## 💡 Consejos para las Capturas de Pantalla
* **Sección de Mensajes:** En los `INSERT` y `UPDATE`, incluye la pestaña *Messages* de pgAdmin para demostrar el éxito de la transacción (`UPDATE 1`, por ejemplo).
* **Bloques de Comprobación:** Captura el resultado de las consultas de **COMPROBACIÓN** para dar evidencia de que los datos cambiaron correctamente en el motor[cite: 1, 2].
