# EverPeak Retail Analysis 

Este repositorio contiene el análisis realizado durante el Sprint 6 del caso EverPeak–SilverBasket. El dataset `everpeak_retail` incluye 2,000 órdenes de clientes con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales del retail. :contentReference[oaicite:2]{index=2}

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Construir un pipeline de limpieza reproducible
- Analizar comportamientos, distribuciones y outliers
- Generar insights para el equipo de Estrategia e Integración de EverPeak

Análisis Exploratorio de Datos para estudiar el comportamiento de indicadores o métricas específicas con estadistica descriptiva (resumen y presentación de variables a partir de valores) y Visualización.

Contexto: El Banco Mundial es un organismo multinacional que brinda asistencia económica y financiera a sus estados asociados. Genera y publicar diversos indicadores macroeconómicos, sociales, demográficos y ambientales que permiten estudiar y contrastar la situación multidimensional entre países cuyo catálogo de información está en https://data.worldbank.org/.

A nivel mundial se reconocen poco más de 200 estados, no todos proveen datos, por lo tanto la entidad si le es posible estima mediante modelos econométricos algunos de estos indicadores faltantes.

En este sentido, buscamos hacer un análisis respecto al comportamiento de la variación del Producto Interno Bruto (PIB) entre los años 2000 y 2023. Enfocado a saber:

¿Cuál ha sido el comportamiento de este indicador en todo el período estudiado?
¿Qué variables inciden principalmente en los cambios a nivel de este indicador?
¿Qué tan probable es que un país tenga una recesión (reducción del PIB) en un año cualquiera?
¿Existen diferencias significativas en el crecimiento de países de "bajo desarrollo" frente a países de "alto desarrollo"?

 Datos disponibles como bases para el análisis:

1. cat_codpais3: [264 filas, 2 columnas] Catálogo que contiene el nombre del país y sus siglas Alpha-3 de acuerdo a la normativa ISO.
2. wb_ahorro: [265, 25] Series anuales 2000 - 2023 por país respecto al porcentaje promedio de ahorro que mantienen los habitantes como porcentaje de su ingreso.
3. wb_crecimpib: [265, 25] Series anuales 2000 - 2023 por país respecto a la tasa de variación del PIB.
4. wb_crecimpob: [265, 25] Series anuales 2000 - 2023 por país respecto a la tasa de variación de la población.
5. wb_poburbana: [265, 25] Series anuales 2000 - 2023 por país respecto al porcentaje de la población que reside en áreas urbanas.
Nota: Cada uno de estos dataframes se encuentra en formato csv. E importar las librerías pandas, numpy y matplotlib.
