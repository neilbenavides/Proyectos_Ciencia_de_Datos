## Descripción del Proyecto

Este repositorio contiene un proyecto de ciencia de datos que explora la relación entre los datos demográficos de las ciudades de Estados Unidos y la calidad del aire en estas ciudades. El objetivo es entender cómo la población y la composición demográfica de una ciudad pueden influir en su calidad del aire, y viceversa.

## Conjunto de Datos Demográficos

El conjunto de datos demográficos se obtuvo de un archivo CSV que contiene información sobre varias ciudades en los Estados Unidos. Este archivo es una rica fuente de información que nos permite entender la composición de la población en diferentes ciudades. Las columnas del DataFrame son las siguientes:

- Ciudad
- Estado
- Edad Media
- Población Masculina
- Población Femenina
- Población Total
- Número de Veteranos
- Nacidos en el Extranjero
- Tamaño Promedio del Hogar
- Código del Estado
- Raza
- Cuenta

Se realizó un proceso de limpieza de datos para tratar los datos faltantes o nulos y eliminar las filas duplicadas. Este proceso es crucial para garantizar la precisión de nuestros análisis posteriores.

## Conjunto de Datos de Calidad del Aire

Utilizando una API, se obtuvieron datos sobre la calidad del aire en las ciudades mencionadas anteriormente. Estos datos se exportaron a un archivo CSV. Las columnas del DataFrame obtenido son las siguientes:

- Ciudad
- CO
- NO2
- O3
- SO2
- PM2.5
- PM10

Al igual que con el conjunto de datos demográficos, se realizó un proceso de limpieza de datos para tratar los datos faltantes o nulos y eliminar las filas duplicadas. Este proceso es igualmente importante para garantizar la validez de nuestros análisis.

## Unión de los Conjuntos de Datos

Se realizó una operación para unir varias columnas de estos dos conjuntos de datos, resultando en un nuevo DataFrame con las siguientes columnas:

- Ciudad
- Población Total
- Estado
- CO
- NO2
- O3
- SO2
- PM2.5
- PM10

Este nuevo DataFrame nos permite analizar la relación entre la población y la calidad del aire en una sola vista.

## Análisis de Datos

Se realizaron varios procesos de filtrado para agrupar y organizar los datos según el número de población y las ciudades donde se presentaron las concentraciones más elevadas de contaminantes. El objetivo de este análisis es determinar si existe alguna relación entre la población y la contaminación ambiental. Este análisis puede revelar patrones interesantes y proporcionar información valiosa para futuras investigaciones.

## Conclusión

Este proyecto proporciona una visión interesante de la relación entre los datos demográficos y la calidad del aire en varias ciudades de los Estados Unidos. Además, este proyecto demuestra el poder de la ciencia de datos para extraer conocimientos valiosos de conjuntos de datos aparentemente dispares.