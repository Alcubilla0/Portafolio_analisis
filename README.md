# Portafolio análisis. Módulo 2
*Inteligencia artificial avanzada para la ciencia de datos I - Portafolio de análisis individual*

**María Fernanda Torres Alcubilla A01285041**

La base de datos a trabajar es [CO2 Emissions](https://www.kaggle.com/datasets/bhuviranga/co2-emissions) y fue obtenida de la plataforma Kaggle, estos cuentan con la licencia de *Database Contents License (DbCL) v1.0*. Esta se encuentra en el archivo *CO2Emissions.csv* dentro de la rama Datos.

Esta rama cuenta con el código de [*Análisis y reporte del desempeño*](Análisis_y_reporte_del_desempeño.ipynb). En este se realiza un modelo de regresión lineal simple, donde se trata de predecir el consumo de combustible en la ciudad a partir de las emisiones de CO2 de un automovil, este modelo de machine learning permite analizar la relación de dos variables a través de una ecuación, con una variable dependiente (a predecir) e independiente (conocida). Además, en el código se encuentra la separación de los datos en sets de entrenamiento, validación y prueba, diagnósticos de grado de sesgo, varianza y nivel de ajuste y se implementan técnicas de regularización para mejorar el desempeño.

***Cambios implementados***

Se añadió un resumen descriptivo de los datos y se implementaron los cálculos de sesgo y varianza correctos, además de la regularización. El grado de sesgo se obtuvo a través del promedio de la diferencia estandarizada entre la predicción y el valor observado, la varianza se obtuvo variando el porcentaje de separación del set de entrenamiento y validación y la regularización al implementar el modelo SGD con distintos parámetros de penalización. 
