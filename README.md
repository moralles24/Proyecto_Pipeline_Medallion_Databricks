# 🚀 Proyecto ETL con Databricks y Arquitectura Medallion

Este repositorio contiene el desarrollo de un **pipeline ETL** implementado en **Databricks**, siguiendo la arquitectura **Medallion (Bronze, Silver, Gold)**. El objetivo es demostrar cómo transformar datos crudos en información lista para análisis y visualización, aportando valor estratégico a la empresa **TechMart**.

---

## 📂 Estructura del Proyecto

- **`/docs`** → Documentación del proyecto (metodología, conclusiones, limitaciones).
- **`/folder`** → Codigo de las etapas del Medallion y las visualizaciones con Pandas.
- **`/jobs`** → Código del Job principal en Databricks.   
- **`Diagrama de Arquitectura`** → Visualizacion sobre la estructura del Proyecto. 

---

## 🏗️ Arquitectura Medallion

- **Bronze:** Captura de datos en su forma original.  
- **Silver:** Procesamiento y estandarización para asegurar calidad.  
- **Gold:** Datos refinados y listos para análisis de negocio.  
---

## ⚙️ Ejecución del Job

El pipeline se ejecuta mediante un **Job en Databricks**, que orquesta las tres capas.  
- Estado final: todas las tareas en **“Succeeded” (verde)** ✅  
- Limitación: en la **Community Edition** la ejecución debe hacerse manualmente, ya que no permite configurar tiempos programados.

---

## 📊 Visualizaciones con Pandas

A partir de la capa **Gold**, se generaron gráficos que permiten extraer conclusiones de negocio:

- **Ventas por sucursal:** desempeño equilibrado entre sedes.  
- **Tendencia mensual:** diciembre 2025 con ventas destacadas.  
- **Top 10 productos más vendidos:** demanda diversificada.  
- **Distribución por categoría:** predominio de Electrónica (70.3%).  

---

## ✅ Conclusiones

- El pipeline asegura **integridad y disponibilidad de los datos**.  
- Las visualizaciones permiten identificar **patrones de ventas y oportunidades de negocio**.  
- Existe una **dependencia comercial en Electrónica**, lo que abre espacio para diversificación.  
- Futuras mejoras: automatización de Jobs en versiones avanzadas de Databricks y análisis de márgenes/estacionalidad.  

---

## 📌 Autor

**Daniel Morales López** – Data Enginner
