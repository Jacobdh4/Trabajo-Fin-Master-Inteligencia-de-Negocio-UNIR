# 🏘️ Análisis Multidimensional del Mercado Residencial de Canarias

**Trabajo de Fin de Máster** — Máster en Inteligencia de Negocio y Análisis de Datos, UNIR
Autor: **Jacob Delgado Hidalgo** · Calificación: Sobresaliente · 2025–2026

[![Dashboard en vivo](https://img.shields.io/badge/Power_BI-Dashboard_interactivo-F2C811?logo=powerbi&logoColor=black)](TU_ENLACE_AQUI)
[![Memoria PDF]([https://img.shields.io/badge/TFM-Memoria_completa_(PDF)-informational)](./docs/TFM_Jacob_Delgado.pdf](https://github.com/Jacobdh4/Trabajo-Fin-Master-Inteligencia-de-Negocio-UNIR/blob/main/An%C3%A1lisis%20Multidimensional%20del%20Mercado%20Residencial%20en%20Canarias%20(2015-2025).pdf))

---

## 📌 Resumen

Análisis del mercado residencial de **88 municipios de Canarias** durante el periodo **2015–2025**, combinando ingeniería de datos, aprendizaje no supervisado y modelos estadísticos para identificar patrones territoriales de precio y construir una herramienta de exploración visual para no técnicos.

El proyecto cubre el ciclo completo: desde la extracción y limpieza de datos brutos hasta un dashboard interactivo listo para la toma de decisiones.

## 🎯 Objetivos

- Integrar fuentes de datos dispersas sobre el mercado residencial canario en un modelo de datos único y consultable.
- Segmentar los municipios según su dinámica de precios mediante clustering no supervisado.
- Modelar los factores que explican la variación de precios mediante regresión.
- Traducir los resultados en un dashboard interactivo que cualquier usuario de negocio pueda explorar sin conocimientos técnicos.

## 🧱 Arquitectura y metodología

| Fase | Descripción | Herramientas |
|---|---|---|
| **ETL** | Extracción, limpieza y transformación de datos de mercado residencial de fuentes públicas | SQL, Power Query |
| **Modelado de datos** | Data Warehouse en esquema **copo de nieve** | SQL Server |
| **Clustering** | Segmentación de los 88 municipios mediante **K-Means**, validado con Método del Codo y Coeficiente de Silueta | R |
| **Modelado estadístico** | Regresión lineal múltiple, con diagnóstico de supuestos (Durbin-Watson, heterocedasticidad, errores robustos) | R |
| **Visualización** | Dashboard interactivo multi-filtro (zona, periodo, tipología de mercado) | Power BI |

## 📊 Dashboard

👉 **[Ver dashboard interactivo](TU_ENLACE_AQUI)**

![Vista previa del dashboard](./docs/dashboard_preview.png)

*(Sustituye la imagen y el enlace anteriores por los tuyos una vez publiques el informe con "Publicar en la Web" desde Power BI.)*

## 📄 Memoria completa

La memoria completa del TFM (101 páginas) está disponible en [`/docs/TFM_Jacob_Delgado.pdf`](./docs/TFM_Jacob_Delgado.pdf), incluyendo marco teórico, metodología detallada, resultados y conclusiones.

## 🗂️ Estructura del repositorio

```
├── docs/
│   ├── TFM_Jacob_Delgado.pdf        # Memoria completa
│   └── dashboard_preview.png        # Captura del dashboard
├── etl/
│   └── ...                          # Scripts de extracción y transformación
├── sql/
│   └── ...                          # Definición del Data Warehouse (esquema copo de nieve)
├── analysis/
│   ├── clustering_kmeans.R          # Segmentación de municipios
│   └── regresion_lineal.R           # Modelo de regresión y diagnósticos
├── dashboard/
│   └── mercado_residencial.pbix     # Archivo Power BI
└── README.md
```

*(Ajusta esta estructura a como tengas realmente organizados tus archivos.)*

## 🔍 Principales hallazgos

- [Añade 2-3 conclusiones clave del TFM, en una línea cada una — son las que más impacto generan al lector que no va a leer las 101 páginas.]

## 🛠️ Tecnologías

`SQL Server` `R` `Power BI` `Power Query` `DAX`

## 📬 Contacto

**Jacob Delgado Hidalgo**
[LinkedIn](https://linkedin.com/in/jacobdelgadoh) · jacobdh04@gmail.com
