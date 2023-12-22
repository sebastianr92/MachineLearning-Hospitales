
# 🚀 Machine Learning Project
Predicción de Hospitalización en Pacientes Sometidos a Biopsia Prostática

Este proyecto de Machine Learning tiene como objetivo realizar un análisis exploratorio de datos (EDA), la preparación y transformación de los datos, y la construcción y evaluación de modelos de Machine Learning para predecir la hospitalización de pacientes sometidos a biopsia prostática. Los modelos utilizados son K-Vecinos y Árboles de Decisión. En el caso de los Árboles de Decisión, se busca determinar el valor óptimo del hiperparámetro de profundidad (K-depth).

## 🌐 Introducción

La aplicación de Machine Learning en Medicina permite el análisis de datos clínicos para emitir diagnósticos predictivos, evaluar la efectividad de estrategias de intervención y anticipar complicaciones en la atención médica. En este proyecto, nos enfocamos en identificar las características más importantes que tienen los pacientes de cierto tipo de enfermedad que terminan en hospitalización después de someterse a una biopsia prostática.

## 🎯 Planteamiento de la Problemática

Nuestro cliente necesita comprender mejor las características que influyen en la hospitalización de pacientes sometidos a biopsia prostática. Se definió como caso a aquel paciente que presentó fiebre, infección urinaria o sepsis en un período máximo de 30 días después de la biopsia prostática, requiriendo manejo médico ambulatorio u hospitalizado para la resolución de la complicación. Como control se considera al paciente que no presentó complicaciones infecciosas en el mismo período.

El conjunto de datos incluye información sobre antecedentes del paciente, morbilidad asociada al paciente, antecedentes relacionados con la toma de la biopsia y complicaciones infecciosas. Debido a problemas de calidad de datos, es necesario realizar un análisis exploratorio y una preparación adecuada de los datos antes de construir modelos de predicción.

## 📊 Diccionario de Datos

A continuación se presenta un diccionario de datos con las variables incluidas en el conjunto de datos:

![image](https://user-images.githubusercontent.com/118769777/220240501-8c21461d-2de5-495b-954e-10fb9bf38014.png)

## 🚧 Desarrollo del Proyecto

El proyecto se divide en tres fases principales:

### 1. Análisis Exploratorio de Datos (EDA)

En esta fase, se realizó un análisis exploratorio de los datos para comprender la calidad de los mismos y obtener información relevante. Se exploraron las distribuciones de las variables, se identificaron valores faltantes y se evaluó la relación entre las características y la hospitalización.

### 2. Preparación de Datos

Se llevaron a cabo diversas tareas de limpieza y transformación de los datos. Se trató el manejo de valores faltantes, la codificación de variables categóricas, y la selección de características relevantes para los modelos de Machine Learning.

### 3. Modelamiento y Evaluación

Se construyeron dos modelos de Machine Learning: K-Vecinos y Árboles de Decisión. En el caso de los Árboles de Decisión, se exploró la búsqueda del hiperparámetro de profundidad óptimo. Se evaluaron los modelos utilizando métricas apropiadas y se seleccionó el mejor modelo.

## 🤖 Modelos de Machine Learning

Para abordar la predicción de hospitalización en pacientes sometidos a biopsia prostática, se implementaron dos modelos de Machine Learning supervisados: K-Vecinos y Árboles de Decisión.

1. **K-Vecinos (K-Nearest Neighbors)**: El modelo K-Vecinos se basa en la idea de que pacientes con características similares tienen un comportamiento similar en términos de hospitalización. Este enfoque de vecinos más cercanos utiliza la distancia entre puntos de datos para clasificar nuevos pacientes en función de la mayoría de K vecinos más cercanos. La elección de K, el número de vecinos considerados, es un hiperparámetro crítico que se exploró durante la fase de modelado.
2. **Árboles de Decisión**: Los Árboles de Decisión son modelos que dividen el conjunto de datos en subconjuntos basados en reglas de decisión. Cada nodo del árbol representa una característica y una decisión, lo que permite clasificar a los pacientes en función de sus características. En este proyecto, se buscó encontrar la profundidad óptima del árbol, un hiperparámetro importante, para garantizar que el modelo no esté sobreajustado ni subajustado.

Ambos modelos se evaluaron utilizando métricas apropiadas, para determinar cuál de ellos proporciona el mejor rendimiento en la predicción de la hospitalización de pacientes. Esta selección se basó en el análisis de los resultados y en la consideración de las características específicas del problema de salud que estamos abordando.

## 🏁 Conclusiones

El proyecto permitió identificar características importantes que influyen en la hospitalización de pacientes sometidos a biopsia prostática. Los modelos de Machine Learning desarrollados brindan una base para predecir la hospitalización y apoyar la toma de decisiones médicas.

Este proyecto demuestra la aplicación de técnicas de Ciencia de Datos en el campo de la medicina, lo que puede resultar en mejoras significativas en la atención de los pacientes.

## 🙏 Agradecimientos

Agradecemos a nuestro cliente y a la consultora por la oportunidad de trabajar en este proyecto. También, agradecemos a nuestros instructores por su orientación y apoyo a lo largo del curso.

**Equipo de Ciencia de Datos**
Kevin Coaguila, Sebastián Risi, Adrián Felipe Pérez Díaz, Carlos G. Cantón, César Chirino.

Octubre 2023
