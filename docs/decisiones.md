# Decisiones de Configuración y Entorno (0.5)

## 1. Formato de Configuración
* **Formato elegido:** `application.yml`
* **Justificación:** Ofrece una estructura jerárquica más limpia, legible y mantenible para gestionar propiedades anidadas y perfiles de Spring, además de facilitar la inyección de variables de entorno desde `.env`.

## 2. Despliegue de PostgreSQL
* **Estrategia:** Contenedor local mediante **Docker Compose** (`docker-compose.yml`).
* **Justificación:** Permite tener un entorno de base de datos aislado, reproducible y liviano en el equipo local sin instalar servicios globales de PostgreSQL en el sistema operativo.

---
> **Nota:** Las versiones exactas de **Java** y **Spring Boot** se registrarán en esta documentación durante el **Paso 1**, al momento de configurarlas en Spring Initializr.