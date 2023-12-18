# Análisis de Insuficiencia Cardíaca 

## Descripción del Proyecto 

Este proyecto se centra en el análisis de un conjunto de datos de registros clínicos de pacientes con insuficiencia cardíaca. El objetivo principal es explorar las relaciones entre diferentes variables y cómo afectan al resultado de la insuficiencia cardíaca.

## Conjunto de Datos 

El conjunto de datos utilizado en este proyecto proviene de registros clínicos de pacientes con insuficiencia cardíaca. Cada registro en el conjunto de datos representa a un paciente individual y contiene la siguiente información:

- **Edad**: La edad del paciente.
- **Anemia**: Si el paciente tiene anemia o no.
- **Creatinina fosfoquinasa**: Nivel de la enzima CPK en la sangre (mcg/L).
- **Diabetes**: Si el paciente tiene diabetes o no.
- **Fracción de eyección**: Porcentaje de sangre que sale del corazón en cada contracción.
- **Presión arterial alta**: Si el paciente tiene hipertensión o no.
- **Plaquetas**: Número de plaquetas en la sangre (kiloplaquetas/mL).
- **Creatinina sérica**: Nivel de creatinina sérica en la sangre (mg/dL).
- **Sodio sérico**: Nivel de sodio sérico en la sangre (mEq/L).
- **Sexo**: Género del paciente.
- **Fumadores**: Si el paciente es fumador o no.
- **Tiempo**: Tiempo de seguimiento (días).
- **Evento de muerte**: Si el paciente falleció durante el período de seguimiento.

## Herramientas Utilizadas 

Este proyecto se realizó utilizando Python, con las siguientes bibliotecas:

- **Pandas**: Para la manipulación y análisis de datos.
- **Numpy**: Para operaciones matemáticas y de matrices.
- **Matplotlib**: Para la visualización de datos.

## Procesamiento de Datos 

El procesamiento de los datos fue una etapa crucial en este proyecto. Antes de poder realizar cualquier análisis, era necesario asegurarse de que los datos estuvieran limpios y listos para ser utilizados.

### Limpieza de Datos 

La limpieza de los datos implicó varias tareas. Primero, busqué valores nulos en el conjunto de datos. Los valores nulos pueden ser problemáticos porque pueden sesgar los resultados del análisis o causar errores. Además, busqué filas duplicadas en el conjunto de datos. Las filas duplicadas pueden distorsionar los resultados del análisis al dar más peso a ciertos registros. 

### Detección de Valores Atípicos 

También realicé una detección de valores atípicos utilizando el rango intercuartil. Los valores atípicos son valores que son significativamente diferentes de otros valores en el conjunto de datos. Pueden ser causados por errores de medición o pueden ser indicativos de algo interesante. En este caso, decidí no tratar los valores atípicos para evitar la distorsión en los resultados del análisis, ya que en datos médicos pueden haber datos con valores altos.


## Análisis de Datos 

El análisis de los datos se realizó en varias etapas. Primero, segmenté los datos por género, edades, personas vivas y personas muertas. Esto me permitió observar las diferencias y similitudes entre estos grupos y entender mejor la distribución de los datos.

Luego, realicé un análisis estadístico para detectar la relación entre las muertes y las enfermedades de los pacientes. Utilicé diversas técnicas de visualización de datos, como gráficos de barras y gráficos de torta, para representar estas relaciones de manera más intuitiva.

Además, utilicé medidas estadísticas, como la media, la mediana y la desviación estándar, para resumir y describir los datos. También realicé pruebas de hipótesis para determinar si las diferencias observadas en los datos eran estadísticamente significativas.

## Resultados 

Los resultados del análisis proporcionaron varias ideas interesantes. Por ejemplo, encontré que ciertas enfermedades estaban más asociadas con la muerte que otras. También observé diferencias en las tasas de muerte entre hombres y mujeres, así como entre diferentes grupos de edad.

Además, los resultados mostraron que ciertos factores, como el tabaquismo y la presión arterial alta, parecían tener un impacto significativo en la insuficiencia cardíaca.

Todos estos resultados se presentan en el repositorio en forma de gráficos y tablas. Cada gráfico y tabla viene acompañado de una descripción detallada que explica lo que representa y cómo se relaciona con el resto del análisis.
