# Machine Learning Pagos Financieros Colombia 

Proyecto de Ciencia de Datos y Big Data

---

## Descripción del Proyecto

Este proyecto desarrolla una herramienta de enriquecimiento y análisis de datos transaccionales financieros utilizando información pública del Formato 413 de la Superintendencia Financiera de Colombia.  

El objetivo principal es transformar datos agregados de operaciones financieras en información estructurada y analíticamente explotable, permitiendo identificar patrones transaccionales, segmentaciones económicas y comportamientos operativos dentro del sistema financiero colombiano.

El proyecto integra técnicas de:

- Enriquecimiento de datos  
- Integración de fuentes externas (CIIU, DIVIPOLA, tablas regulatorias)  
- Análisis exploratorio de datos  
- Modelos de Machine Learning supervisado y no supervisado  
- Construcción de pipeline analítico reproducible  

---

## Objetivos

- Diseñar un proceso de enriquecimiento de datos financieros basado en clasificación CIIU y segmentación geográfica.  
- Construir variables derivadas que aumenten el valor analítico del dataset original.  
- Aplicar técnicas de clustering para identificar patrones de comportamiento transaccional.  
- Implementar modelos supervisados para clasificación o predicción de categorías económicas.  
- Evaluar el impacto del enriquecimiento en la capacidad explicativa de los modelos.  

---

## Fuente de Datos

**Dataset:** Formato 413 – Operaciones efectuadas a través de los canales de distribución o servicios transaccionales  
**Entidad:** Superintendencia Financiera de Colombia  
**Portal:** Datos Abiertos Colombia  

El conjunto de datos incluye información sobre:

- Tipo de entidad financiera  
- Canal de distribución  
- Servicio transaccional  
- Actividad económica (CIIU)  
- Ubicación geográfica (Departamento y Municipio – DIVIPOLA)  
- Tipo de persona  
- Cantidad de operaciones  
- Monto de operaciones  

**Periodo de actualización:** Enero 2025  
**Volumen aproximado:** 10 millones de registros  

---

## Arquitectura del Proyecto

El proyecto se estructura en las siguientes etapas:

1. Ingesta y limpieza de datos  
2. Integración con tablas regulatorias auxiliares  
   - Tabla CIIU  
   - Tabla Canal  
   - Tabla Servicios  
   - Tabla Tipo de Persona  
   - Codificación DIVIPOLA  
3. Proceso de enriquecimiento  
4. Feature engineering  
5. Análisis exploratorio  
6. Modelado  
7. Evaluación de resultados  

---

## Técnicas Aplicadas

- Limpieza y transformación de datos con Python  
- Manejo de grandes volúmenes de datos  
- Ingeniería de características  
- Clustering (K-Means u otros algoritmos no supervisados)  
- Modelos supervisados de clasificación  
- Evaluación con métricas de desempeño  
- Visualización analítica  

---

## Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Lab  / Jupyter Notebook 

---

## Aplicabilidad

Este proyecto puede ser aplicado en:

- Entidades financieras  
- Fintech  
- Análisis regulatorio  
- Inteligencia de negocio  
- Sistemas de categorización automática de pagos  
- Modelos de comportamiento transaccional  

---

## Autor

**Andrés Felipe Salazar Daza**  



