# API Quality Assurance & Contract Testing - Nager.Date API

Proyecto profesional de automatización y  pruebas de API REST utilizando **Postman**, **Newman** y **JavaScript**, validando contratos, esquemas JSON, pruebas negativas, análisis de valores límite (Boundary Value Analysis) y líneas base de rendimiento.

## Tecnologías y Herramientas
* **Postman / Newman:** Pruebas automatizadas y ejecución en línea de comandos.
* **Chai Assertion Library & JSON Schema:** Validación estricta de esquemas y contratos de datos.
* **JavaScript (Node.js):** Scripts dinámicos en *Pre-request* y *Tests* (cálculo de fechas relativas, manejo de zonas horarias `America/Argentina/Cordoba`).
* **Control de Versiones:** Git & GitHub.

---

## Estructura del Proyecto
```text
├── Nager.Date API - QA.postman_collection.json         # Colección principal (Smoke, Contract, Functional, Negative, Perf)
├── Nager.Date - PERF-002 - Estabilidad.postman_collection.json # Colección de pruebas de estabilidad
├── Nager_Date_QA_Environment_SANITIZED.json            # Variables de entorno saneadas (baseUrl, countryCode, year, etc.)
└── Matriz_Completa_Nager_Date_QA.xlsx                  # Matriz de pruebas detallada (Trazabilidad 100%)
