# Documentación — Loop Gestión

```
Documentacion/
├── 01_Documentos_IEEE/
│   ├── SRS_Requisitos               requisitos funcionales y no funcionales, reglas de negocio, historias (ISO/IEC/IEEE 29148)
│   ├── Arquitectura_Diseno          decisiones, componentes, modelo de datos, secuencia, contrato de la API, CI (IEEE 1016)
│   ├── Plan_Pruebas                 niveles, criterios y 32 casos de prueba (IEEE 829)
│   └── Articulo_IEEE_LoopGestion    artículo a dos columnas en formato IEEE
├── 02_Matrices/
│   ├── Product_Backlog_e_Historias.xlsx   6 PBI de Azure, 3 sprints y 13 historias de usuario
│   ├── Trazabilidad_Requisitos.xlsx       requisito → historia → caso de uso → mockup → caso de prueba; verificación de RNF
│   ├── Casos_Prueba.xlsx                  32 casos con resultado y evidencia por diligenciar
│   ├── Matriz_Riesgos.xlsx                10 riesgos con exposición calculada
│   ├── Cumplimiento_Guia.xlsx             checklist de la asignatura frente a la evidencia
│   └── Matriz_Maestra.xlsx                inventario de entregables
├── 03_Manuales/                     Manual_Usuario · Manual_Tecnico · Manual_Instalacion
├── 04_Casos_Uso_y_Prueba/           Casos_Uso (11 casos con flujos) + diagrama
├── 05_Mockups/                      10 pantallas, vistas generales y documento de mockups
├── 06_Seguridad_IA/                 Seguridad_y_LoopBot: controles, SAST, DAST y agente de IA
└── Modelos_Datos/                   arquitectura, E-R, navegación, secuencia y casos de uso (png + fuente Mermaid)
```

**Fuentes:** proyecto Loop-Gestion en Azure DevOps (backlog, sprints, tablero, repositorio y pipeline al 4 de noviembre de 2026) y los mockups de la aplicación. Los datos que dependen del código fuente (rutas exactas de la API, nombres de tablas y variables, versiones) están marcados con «⚠ Por confirmar con el código».
