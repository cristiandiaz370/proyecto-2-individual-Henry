<p align=center><img src=https://github.com/cristiandiaz370/proyecto-1-individual-Henry/assets/167250663/4fafcd79-690e-4324-9bc3-cf7fbbd238ad><p>

# <h1 align=center> **Proyecto Final individual #2** </h1>

# <h1 align=center> **Data Analyst sobre Análisis de Siniestros Viales en la Ciudad de Buenos Aires 2016-2021** </h1>

<p align='center'>
<img src="https://cdn.aarp.net/content/dam/aarp/auto/2021/05/1140-minor-fender-bender-esp.imgcache.rev.web.700.402.jpg" alt="Accidente de tránsito">
</p>

## INTRODUCCION

Las estadísticas derivadas de los datos de accidentes de tráfico, tanto fatales como no fatales, tienen como principal objetivo comprender las características demográficas de las víctimas y las circunstancias de los eventos. Estos datos son fundamentales para implementar medidas preventivas y realizar mejoras necesarias para evitar estos trágicos sucesos.

Las graves implicaciones sociales de las muertes en accidentes de tráfico se suman al alto costo humano de pérdidas que podrían haberse evitado.

## DESCRIPCION DEL PROYECTO

El objetivo de este proyecto es analizar los accidentes de tráfico en la Ciudad de Buenos Aires utilizando datos recopilados por el Observatorio de Movilidad y Seguridad Vial (OMySV) entre 2016 y 2021. El análisis busca identificar patrones, tendencias y factores de riesgo relacionados con estos accidentes, con el propósito de proporcionar información útil para la toma de decisiones por parte de las autoridades locales y para la prevención de futuros incidentes.

Sin embargo, es importante tener en cuenta una particularidad significativa: aunque el censo de 2022 del Gobierno Argentino reporta una población estable de 3,121,707 habitantes en la Ciudad Autónoma de Buenos Aires, aproximadamente 3.5 millones de personas ingresan diariamente desde los municipios del Gran Buenos Aires. Esta diferencia tan significativa hace que cualquier cálculo de indicadores clave de rendimiento (KPIs) basado únicamente en datos del censo resulte inexacto y poco representativo de la situación real.

## CONTENIDO DEL REPOSITORIO

CSV/: Carpeta que contiene los dataset en formato csv, ya limpios con dos hojas de datos: "hechos" y "víctimas", así como diccionarios de datos adicionales para una mejor comprensión de la información.

Notebooks/: Carpeta que contiene los notebook de Jupyter con el ETL del archico original en formato xslx y el análisis exploratorio de datos (EDA) realizado.

dashboards generado durante el análisis.

## TECNOLOGIAS Y HERRAMIENTAS UTILIZADAS

Para el desarrollo del EDA (*Exploratory Data Analysis*), se utilizaron las siguientes herramientas y tecnologias:

![VSCode](https://img.shields.io/badge/-VSCode-333333?style=flat&logo=visual-studio-code)
![Python](https://img.shields.io/badge/-Python-333333?style=flat&logo=python)
![Jupyter](https://img.shields.io/badge/-Jupyter-333333?style=flat&logo=jupyter)
![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-333333?style=flat&logo=WordCloud)
![Seaborn](https://img.shields.io/badge/Seaborn-333333?style=flat&logo=Seaborn)

Para el desarrollo del dashboard, se utilizaron las siguientes herramientas:

![PowerBI](https://img.shields.io/badge/PowerBI-333333?style=flat&logo=powerbi)

## REPORTE DEL ANALISIS

Se trabajó con el archivo homicidios.xlsx, el cual fue sometido a un proceso de ETL (extracción, transformación y carga) y de EDA (Análisis Exploratorio de Datos).

En el notebook ETL.ipynb, se examinaron, limpiaron y validaron diferentes aspectos de los datos, como la detección y manejo de valores faltantes, outliers y duplicados.

El análisis exploratorio de datos (EDA) se encuentra documentado en el notebook EDA.ipynb en la carpeta notebooks/. En este notebook se presentan gráficos y se resumen las conclusiones relevantes obtenidas durante el análisis de los datos.

KPIs Propuestos
1. Reducción de la Tasa de Homicidios en Siniestros Viales
Se propone reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en comparación con la tasa del semestre anterior. La fórmula para calcular la tasa de homicidios en siniestros viales es: (Número de homicidios en siniestros viales / Población total) * 100,000.

2. Reducción de Accidentes Mortales de Motociclistas
Se propone reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en comparación con el año anterior.

## RECOMENDACIONES AL GOBIERNO DE LA CIUDAD:

Se han propuesto medidas para mejorar el tráfico y la seguridad vial que son simples, fáciles de implementar de inmediato y han demostrado tener un impacto rápido y efectivo en la sociedad, basándose en experiencias exitosas a nivel internacional:

* Implementar campañas de concientización sobre seguridad vial.

* Controlar prioritariamente el respeto absoluto por el semáforo en rojo y la prioridad peatonal.

* Impedir en forma efectiva el estacionamiento en las avenidas y calles de mayor tránsito, en ambas manos, máxime cuando lo es en doble o triple fila.

* Fortalecer los controles vehiculares y aplicar sanciones más severas para las infracciones.

* Mejorar la infraestructura vial, incluyendo señalización, mantenimiento y diseño adecuado.

* Priorizar la seguridad de los grupos más vulnerables: motociclistas, peatones y jóvenes conductores.

* Implementar medidas específicas en las zonas y horarios de mayor riesgo.

### Es fundamental reconocer que la seguridad vial es una responsabilidad compartida por todos los involucrados en el sistema de tránsito: conductores, peatones, ciclistas y autoridades. Solo trabajando juntos de manera continua y coordinada podremos disminuir el número de accidentes de tráfico con consecuencias fatales.

