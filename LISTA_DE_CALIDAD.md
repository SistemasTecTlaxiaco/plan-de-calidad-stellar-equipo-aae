#  Plan de Calidad – Proyecto Stellar Token Launchpad (SCF)

## 1. Introducción
Este documento presenta el **Plan de Calidad** del proyecto **Stellar Token Launchpad**, desarrollado en el marco de la Stellar Community Fund (SCF).  
El objetivo es asegurar que el producto final cumpla con los estándares de calidad definidos, garantizando seguridad, confiabilidad, usabilidad y satisfacción de la comunidad.  

Este plan está alineado con principios de **CMMI** y **MoProSoft**, enfocándose en gestión de requisitos, desarrollo de software, gestión de configuración y aseguramiento de calidad.

---

## 2. Gestión de la Calidad del Proyecto

### 2.1. Métricas de Calidad
Para medir la calidad del proyecto, se definen las siguientes métricas:

- **Contratos inteligentes (Rust/Soroban):**
  - % de pruebas unitarias aprobadas.  
  - Objetivo: >85%.  

- **Frontend (Vue 3):**
  - Tiempo promedio de carga de la interfaz.  
  - Objetivo: <2 segundos.  

- **API y red Stellar:**
  - Tiempo de respuesta.  
  - Objetivo: <500 ms.  

- **Seguridad:**
  - Número de vulnerabilidades críticas.  
  - Objetivo: 0.  

- **Satisfacción del usuario (beta testers):**
  - Calificación promedio en encuestas de retroalimentación.  
  - Objetivo: >4 de 5.  

---

## 3. Procedimientos y Actividades de Calidad

### 3.1. Procedimientos de Revisión
- **Revisión de requisitos:** Validación inicial con el equipo y la comunidad SCF antes del desarrollo.  
- **Revisión de arquitectura:** Validación de flujos de creación y gestión de tokens.  
- **Revisión de código (Code Review):** Cada *pull request* será revisado por al menos un miembro del equipo antes de fusionarse con la rama principal.  

### 3.2. Políticas de Pruebas
- **Pruebas unitarias:** Cada funcionalidad de los contratos Soroban debe contar con pruebas automatizadas.  
- **Pruebas de integración:** Validación de la conexión entre la dApp, la red Stellar y la billetera Freighter.  
- **Pruebas de usabilidad:** Sesiones con usuarios beta para asegurar una interfaz intuitiva.  
- **Auditoría de seguridad:** Evaluación externa de los contratos inteligentes antes del despliegue en mainnet.  

---

## 4. Gestión de la Configuración y Liberación

- **Repositorio:** GitHub será el repositorio principal del proyecto.  
- **Control de versiones:** Uso de ramas por funcionalidad (ejemplo: `feature/crear-token`, `feature/conectar-freighter`).  
- **Versionado:** Versionado semántico (ejemplo: `v1.0.0`).  
- **Plan de liberación:**  
  1. Pruebas internas.  
  2. Pruebas con usuarios beta.  
  3. Despliegue en mainnet.  

---

## 5. Documentación

- **Documentación de código:** El código fuente deberá estar comentado y legible.  
- **Manual del usuario:** Guía práctica para que los usuarios puedan crear y lanzar su token.  
- **Documentación de arquitectura:** Diagrama y descripción de la interacción entre la dApp, los contratos Soroban y la red Stellar.  

---

## ✅ Conclusión
Este **Plan de Calidad** proporciona una guía estructurada para garantizar que el Stellar Token Launchpad cumpla con los estándares técnicos y las expectativas de la comunidad SCF.  
Su aplicación permitirá entregar un producto **seguro, confiable y usable**, alineado con las mejores prácticas de calidad de software.
