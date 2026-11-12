# ∞ Loop Gestión — Plataforma académica full-stack con automatización e IA

**Universidad de San Buenaventura, Bogotá · Optativa II (10348) — Desarrollo de Aplicaciones para Dispositivos Móviles · 2026-II**
**Docente:** MGTR. Ing. Jairo Armando Salcedo Aranda
**Integrantes:** Sebastián Grande Moreno · Juan Carlos Díaz Cifuentes

Loop Gestión es una aplicación móvil nativa en Android (Kotlin) con arquitectura cliente-servidor en Node.js/Express y MySQL en Docker, para gestionar actividades académicas, entregas por asignatura y boletín de calificaciones, con el asistente inteligente **LoopBot IA** y notificaciones automáticas mediante **Make.com**.

## Funcionalidades
- Registro e inicio de sesión por rol (Estudiante / Docente) con **Firebase Authentication** y matrícula por materias.
- **Estudiante:** inicio con KPIs, detalle de actividades, envío de entregas, boletín de notas y LoopBot IA.
- **Docente:** materias, calendario de actividades (con calendario nativo de Android), creación de actividades y calificación de entregas.
- **Make.com:** al publicar una actividad, correo a los estudiantes (Gmail) y registro en Google Sheets.
- **CI/CD:** pipeline en Azure Pipelines; gestión Scrum en Azure Boards.

## Tecnologías
Kotlin · Retrofit · Node.js + Express · MySQL · Docker · Firebase Authentication · Make.com · Azure DevOps

## Documentación
Toda la documentación está en [`Documentacion/`](Documentacion/README.md), en Word y PDF:

| Carpeta | Contenido |
|---|---|
| `01_Documentos_IEEE` | SRS de requisitos, arquitectura y diseño, plan de pruebas y artículo en formato IEEE |
| `02_Matrices` | Product backlog e historias, trazabilidad, casos de prueba, riesgos, cumplimiento y matriz maestra (Excel) |
| `03_Manuales` | Manual de usuario, técnico e instalación |
| `04_Casos_Uso_y_Prueba` | Especificación de casos de uso y diagrama UML |
| `05_Mockups` | 10 pantallas (estudiante y docente) y documento de mockups |
| `06_Seguridad_IA` | Controles de seguridad, análisis estático y dinámico, LoopBot IA |
| `Modelos_Datos` | Diagramas de arquitectura, E-R, navegación, secuencia y casos de uso |

## Gestión del proyecto
Azure DevOps (Boards, Repos y Pipelines): https://dev.azure.com/juancarlosdiazlisa/Loop-Gestion
Sprints: 1) Análisis, requisitos, diseño y Auth (7–20 oct) · 2) Funcionalidades principales (21 oct–3 nov) · 3) Make.com, chatbot IA, pruebas y despliegue (4–17 nov).
