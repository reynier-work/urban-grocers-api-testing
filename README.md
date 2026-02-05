# QA API Testing: Urban Grocers - Validación de Servicios de Entrega y Kits

## 📌 Descripción del Proyecto
Este proyecto consistió en el análisis y validación técnica de la API de **Urban Grocers** tras la implementación de nuevas actualizaciones en la plataforma respecto al manejo de kits y servicios de entrega. El objetivo principal fue garantizar que la API admita correctamente los nuevos requisitos de negocio sin comprometer la integridad de los datos existentes.

## 🛠️ Tecnologías y Herramientas
* **Postman:** Ejecución de pruebas, validación de endpoints e interacciones solicitud-respuesta.
* **Jira:** Gestión de defectos y documentación de informes de errores detallados.
* **Swagger / ApiDoc:** Análisis y consulta de la documentación técnica de la API para el diseño de casos de prueba.

## 🚀 Logros Técnicos y Habilidades Aplicadas
Basado en la evaluación y aprobación del proyecto:

* **Análisis Profundo de API:** Verificación de protocolos de intercambio de datos y validación de la exactitud de los datos en 4 endpoints específicos.
* **Estrategias de Diseño de Pruebas:** Implementación exitosa de técnicas de **clases de equivalencia**, **análisis de valores límite**, y ejecución de pruebas tanto **negativas como positivas**.
* **Gestión de Defectos de Alta Calidad:** Documentación de informes de errores con títulos claros (incluyendo método, URL y descripción) y cuerpos de solicitud/respuesta detallados en Jira.
* **Atención al Detalle:** Estructuración de listas de comprobación claras y profesionales, garantizando que los escenarios de prueba cubrieran una amplia gama de comportamientos de la API.

## 📋 Resumen de Pruebas Realizadas
| Método | Endpoint | Objetivo de la Prueba | Resultado |
| :--- | :--- | :--- | :--- |
| GET | `/api/v1/kits` | Validar la recuperación correcta de kits actualizados. | Pasado |
| POST | `/api/v1/orders` | Verificar la creación de órdenes con servicios de entrega específicos. | Pasado |
| PUT | `/api/v1/kits/:id` | Probar la modificación de kits bajo nuevos requisitos. | Pasado |
| DELETE | `/api/v1/orders/:id` | Asegurar la eliminación correcta de servicios según la lógica de negocio. | Pasado |

## 📸 Evidencias

]<img width="1144" height="826" alt="Captura de pantalla 2026-02-05 111717" src="https://github.com/user-attachments/assets/61b87482-989f-4fad-bbee-ada15e349009" />

![Tests de Postman]<img width="1152" height="864" alt="Captura de pantalla 2026-02-05 112927" src="https://github.com/user-attachments/assets/d96f32d4-2dd2-4410-ac67-075fe4ce777e" /> 
<img width="1152" height="864" alt="Captura de pantalla 2026-02-05 113113" src="https://github.com/user-attachments/assets/85e890ba-89c3-4756-a3d8-2e857f8d9887" />


---
**Proyecto realizado como parte del Bootcamp QA Engineer en TripleTen.**
