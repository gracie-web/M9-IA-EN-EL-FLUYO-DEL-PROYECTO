# RetailPro — Proyecto de Análisis de Datos

## 1. Descripción del proyecto

RetailPro es un proyecto académico de análisis de datos desarrollado para una empresa distribuidora de tecnología.

El proyecto surge de la necesidad de organizar información comercial que inicialmente se encontraba dispersa en planillas Excel, dificultando el seguimiento de las ventas, los clientes y los productos.

El objetivo principal es construir un sistema de análisis que permita transformar los datos en información útil para la toma de decisiones comerciales.

## 2. Objetivos del proyecto

- Diseñar e implementar una base de datos relacional.
- Organizar la información comercial.
- Aplicar consultas SQL para obtener indicadores de negocio.
- Relacionar las tablas mediante JOINs.
- Preparar y transformar los datos mediante procesos ETL.
- Construir un modelo analítico en Power BI.
- Desarrollar indicadores y un dashboard ejecutivo.

## 3. Herramientas utilizadas

| Herramienta | Aplicación |
|---|---|
| SQL Server | Administración de la base de datos |
| SQL Server Management Studio (SSMS) | Creación y ejecución de consultas |
| SQL | Extracción y análisis de información |
| Power BI | Modelado y visualización de datos |
| Power Query | Limpieza y transformación ETL |
| DAX | Creación de medidas e indicadores |
| ChatGPT | Asistencia en documentación, optimización y análisis |

## 4. Base de datos

**Nombre:** `Ventas_Tech_DB`

**Motor:** Microsoft SQL Server.

Tablas principales:

- `ventas`: registra las operaciones comerciales.
- `clientes`: contiene la información de los clientes.
- `productos`: contiene los artículos comercializados.
- `categorias`: permite clasificar los productos.

La tabla de ventas se relaciona con clientes y productos mediante sus respectivas claves foráneas.

## 5. Desarrollo del proyecto

El proyecto se desarrolla en diferentes etapas:

### Etapa 1 — Análisis del problema

Identificación de las necesidades comerciales y definición de preguntas de análisis, indicadores KPI y objetivos del dashboard.

### Etapa 2 — Diseño de la base de datos

Diseño del modelo relacional, identificación de claves primarias y foráneas y aplicación de criterios de normalización.

### Etapa 3 — Implementación SQL

Creación de la base de datos, definición de tablas y carga de registros mediante SQL Server.

### Etapa 4 — Consultas de negocio

Desarrollo de consultas para analizar:

- Facturación mensual.
- Cantidad de ventas.
- Ticket promedio.
- Ranking de productos.
- Unidades vendidas.

### Etapa 5 — Consultas con JOINs

Integración de información de ventas, clientes y productos para enriquecer el análisis comercial.

### Etapa 6 — Transformación ETL

Utilización de Power Query para limpiar, transformar y estructurar los datos antes de su utilización en el modelo analítico.

### Etapa 7 — Modelado y visualización

Creación de relaciones entre tablas, calendario, medidas DAX y dashboard ejecutivo en Power BI.

### Etapa 8 — Documentación y optimización con IA

Utilización de inteligencia artificial como herramienta de apoyo para revisar consultas SQL, generar insights, documentar el proyecto y validar los resultados.

## 6. Scripts SQL del proyecto

Los principales archivos desarrollados son:

| Archivo | Descripción |
|---|---|
| `ventas_tech_db.sql` | Creación y carga de la base de datos. |
| `m4_consultas_negocio.sql` | Consultas de indicadores comerciales. |
| `m5_consultas_joins.sql` | Consultas para relacionar las tablas mediante JOINs. |

## 7. Cómo ejecutar los scripts SQL

Requisitos previos:

- Microsoft SQL Server instalado.
- SQL Server Management Studio (SSMS).
- Archivos SQL del proyecto.

Procedimiento:

1. Abrir SQL Server Management Studio.
2. Conectarse al servidor de SQL Server.
3. Abrir y ejecutar `ventas_tech_db.sql`.
4. Verificar la creación de la base `Ventas_Tech_DB`.
5. Abrir `m4_consultas_negocio.sql`.
6. Seleccionar la base de datos y ejecutar las consultas.
7. Abrir `m5_consultas_joins.sql` y ejecutar las consultas de integración.
8. Verificar los resultados obtenidos antes de utilizarlos en Power BI.

## 8. Integración con Power BI

Los datos obtenidos desde SQL Server se utilizan como fuente para Power BI.

El proceso contempla:

- Conexión de Power BI con SQL Server.
- Transformación y limpieza mediante Power Query.
- Preparación de tablas de dimensiones y hechos.
- Creación de relaciones.
- Incorporación de una tabla calendario.
- Desarrollo de medidas DAX.
- Construcción del dashboard ejecutivo.

## 9. Resultados esperados

El proyecto busca proporcionar a RetailPro una herramienta de análisis que permita:

- Conocer la evolución de la facturación.
- Identificar los productos más relevantes.
- Analizar el comportamiento comercial.
- Obtener indicadores para evaluar el desempeño.
- Facilitar la toma de decisiones basada en datos.

## 10. Uso de inteligencia artificial

ChatGPT se utilizó como copiloto durante el desarrollo del proyecto para:

- Revisar y optimizar consultas SQL.
- Interpretar resultados de consultas comerciales.
- Identificar oportunidades de mejora.
- Generar documentación técnica.
- Validar sugerencias mediante criterio analítico propio.

Las respuestas generadas por IA fueron consideradas propuestas de trabajo y verificadas contra la estructura real de la base de datos y los resultados obtenidos.

---

**Proyecto académico: RetailPro**

**Tecnologías principales:** SQL Server y Power BI.
