# Proyecto de Análisis de Accidentes Aéreos

Este proyecto tiene como objetivo realizar un análisis detallado de los accidentes aéreos ocurridos entre 1908 y 2021. Durante los últimos más de 100 años, la industria de la aviación ha experimentado grandes procesos de crecimiento y evolución. Detrás de este progreso, encontramos desafíos en términos de seguridad debido a la gran cantidad de accidentes que han ocurrido a lo largo de este período.
![Logo](https://github.com/agusvaldes/PI2-accidentes-aereos/blob/main/Imagenes_dashboard/portada.png)

## Descripción del Proyecto

El proyecto se basa en un conjunto de datos recopilados de fuentes públicas que contienen información sobre accidentes aéreos, incluyendo detalles sobre la aerolínea, ubicación, número de víctimas, periodo, entre otros. El objetivo principal es analizar estos datos para identificar patrones y tendencias, así como proporcionar información valiosa sobre la seguridad en la industria de la aviación. 
[dataset](https://github.com/agusvaldes/PI2-accidentes-aereos/blob/main/AccidentesAviones.csv)

## Exploratory Data Analysis (EDA) 
[notebook](https://github.com/agusvaldes/PI2-accidentes-aereos/blob/main/PI_DataAnalytics.ipynb)

Durante el EDA, se llevaron a cabo las siguientes etapas de análisis:

1. Limpieza y preprocesamiento de los datos:
   - Eliminación de duplicados y valores faltantes.
   - Transformación y ajuste de los tipos de datos según sea necesario.
   - Creación de nuevas columnas necesarias.
   
2. Análisis estadístico y visualización de los datos:
   - Exploración de variables clave como la tasa de supervivencia, la tasa de mortalidad y la ubicación de los accidentes.
   - Creación de gráficos y visualizaciones para identificar patrones y relaciones entre las variables.

3. Identificación de aerolíneas con alta siniestralidad:
   - Tipos de categorias en los aviones.
   - Análisis de las aerolíneas con mayor número de accidentes y su tasa de supervivencia.
   - Identificación de aquellas aerolíneas que han implementado medidas exitosas de seguridad en relación a los accidentes aéreos.
   
## Dashboard

El dashboard consta de 1 portada y 3 páginas navegables a través de una botonera de navegación.

En la primer página se puede observar un análisis general de los datos, describiendo:

* Número total de accidentes,
* Total de fallecidos y total de sobrevivientes,
* Cantidad de accidentes por periodo,
* Tipo de avión, 
* Proporción por categoria,
* Distribución de aerolineas con más accidentes.
![Logo](https://github.com/agusvaldes/PI2-accidentes-aereos/blob/main/Imagenes_dashboard/pag1.png)

En la segunda página, se presentan dos KPIs:

#### KPI 1: Reducción de la Tasa de Mortalidad

En este gráfico de línea, se representa la reducción anual de la tasa de mortalidad. Se destacan aquellos años en los que se logró una reducción significativa del 5% en comparación con el año anterior. Además, se incluye un medidor que indica el porcentaje de reducción de la tasa de mortalidad.

#### KPI 2: Reducción de la Tasa de Accidentes en Estados Unidos

En este gráfico de línea, se muestra la reducción anual de la tasa de accidentes en Estados Unidos. Se resaltan aquellos años en los que se logró una reducción del 5% en comparación con el año anterior. También se incluye un medidor que indica el porcentaje de reducción de la tasa de accidentes en Estados Unidos.
![Logo](https://github.com/agusvaldes/PI2-accidentes-aereos/blob/main/Imagenes_dashboard/pag2.png)

En esta última página, se presentan los siguientes KPIs:

#### KPI 3: Accidentes en Agua

En este gráfico de barras, se visualiza el total de accidentes que han ocurrido en agua. La barra correspondiente a cada ubicación (mar, océano, río, etc.) representa el número de accidentes en los que la superficie se registra como "verdadera" (es decir, los accidentes ocurrieron en agua).

#### KPI 4: Tasa de Supervivencia en Aerolíneas con Alta Siniestralidad

En este gráfico de línea, se muestra la tasa de supervivencia anual en aerolíneas con alta siniestralidad. Se resaltan aquellas aerolíneas que han tenido éxito en implementar medidas de seguridad efectivas en relación a los accidentes aéreos, y además, se grafica una tabla con las marcas de los aviones que compraron estas aerolineas.
![Logo](https://github.com/agusvaldes/PI2-accidentes-aereos/blob/main/Imagenes_dashboard/pag3.png)
