# 🏘️ Análisis Multidimensional del Mercado Residencial de Canarias

**Trabajo de Fin de Máster** — Máster en Inteligencia de Negocio y Análisis de Datos, UNIR
Autor: **Jacob Delgado Hidalgo** · Calificación: Sobresaliente · 2025–2026

[![Dashboard en vivo](https://img.shields.io/badge/Power_BI-Dashboard_interactivo-F2C811?logo=powerbi&logoColor=black)](https://github.com/Jacobdh4/Trabajo-Fin-Master-Inteligencia-de-Negocio-UNIR/blob/main/Dashboard%20-%20An%C3%A1lisis%20del%20Mercado%20Residencial%20en%20Canarias%20(2015-2025).pbix)

[![Memoria PDF](https://img.shields.io/badge/TFM-Memoria_completa_(PDF)-informational)](./Análisis%20Multidimensional%20del%20Mercado%20Residencial%20en%20Canarias%20(2015-2025).pdf)

---

## 📌 Resumen

Análisis del mercado residencial de **88 municipios de Canarias** durante el periodo **2015–2025**, combinando ingeniería de datos, aprendizaje no supervisado y modelos estadísticos para identificar patrones territoriales de precio y construir una herramienta de exploración visual para no técnicos.

El proyecto cubre el ciclo completo: desde la extracción y limpieza de datos brutos hasta un dashboard interactivo listo para la toma de decisiones.

## 🎯 Objetivos

- Integrar fuentes de datos diversas sobre el mercado residencial canario en un modelo de datos único.
- Segmentar los municipios según variables relevantes mediante clustering (Aprendizaje no supervisado).
- Descubrir los factores que explican la variación de precios en el mercado residencial de Canarias mediante regresión.
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

👉 **[Ver dashboard interactivo](https://github.com/Jacobdh4/Trabajo-Fin-Master-Inteligencia-de-Negocio-UNIR/blob/main/Dashboard%20-%20An%C3%A1lisis%20del%20Mercado%20Residencial%20en%20Canarias%20(2015-2025).pbix)**

👉 **[Ver vista previa del dashboard](https://github.com/Jacobdh4/Trabajo-Fin-Master-Inteligencia-de-Negocio-UNIR/blob/main/2.%20Vista%20Previa%20-%20Dashboard%20-%20An%C3%A1lisis%20del%20Mercado%20Residencial%20en%20Canarias%20(2015-2025).pdf)**

## 📄 Memoria completa

La memoria completa del TFM (101 páginas) está disponible en [![Memoria PDF](https://img.shields.io/badge/TFM-Memoria_completa_(PDF)-informational)](./Análisis%20Multidimensional%20del%20Mercado%20Residencial%20en%20Canarias%20(2015-2025).pdf), situándose en los anexos capturas del dashboard y los 
códigos de R para clustering, regresión e imputación de datos entre otros

## 🔍 Principales hallazgos

- El paso del tiempo es el factor que más se asocia a las variaciones de los precios. No es el paso del tiempo en sí, sino que oculta variables intrínsecas difícilmente medibles (inflación, falta de oferta de vivienda, suelo urbanizable...)
- La densidad de vivienda vacacional es la siguiente variable que más se asocia con las variaciones, por encima de la renta o el desempleo.
- El análisis por clústeres permite segmentar municipios según su poder adquisitivo y tasa de desempleo, superando el enfoque de tratar el territorio como un bloque homogéneo. Se distinguen 3 clústeres (0,49 IS) segmentando los municipios en zonas urbanas; zonas tensionadas y zonas poco diferenciadas.
- Los modelos predictivos muestran que cada punto porcentual de aumento en la densidad de vivienda vacacional se puede aumentar el precio de compraventa en un 1,34% y el de alquiler en un 0,60%. El paso de los años se asocia con un 5,75% y un 6,38% de aumento, respectivamente.

## 🛠️ Tecnologías

`SQL Server` `R` `Power BI` `Power Query` `DAX`

## 📬 Contacto

**Jacob Delgado Hidalgo**
[LinkedIn](https://linkedin.com/in/jacobdelgadoh) · jacobdh04@gmail.com
